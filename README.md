<img src="assets/laravel-lighthouse.png" alt="table and columns from each" style="float: left; width: 10px; height:10px; text-align: center"/>

# Laravel GraphQL
To learn a little about GraphQL, I made a simple project that makes the relationship between users and posts with content and title, and here's what I did

## What was done ?!

**Two tables were created, using MySQL, one that shows users, and the other that shows posts, the content of each table is:**

| users |  posts  |
|:-----:|:-------:|
|  name |  author |
| email |  title  |
|       | content |

```
The relationships between them occur in the author, who uses the id of each user who generates a post
```

## How to run in my local ?!

It's very simple you just need to have the **docker** and **docker-compose** installed.<br/> 
With that installed just run the following command

```shell
 $ docker-compose up -d
```

You will already have the PHPMyAdmin environment to orchestrate your bank, access URL <br/>
`http://localhost:9001`

## How to test

To test you will need an environment to test HTTP calls.<br/>
My indications:
 - Altair (Linux tool)
 - GraphQL Playground (Extension chrome, or install in your computer)

In your environment access the route <br/>
`http://localhost:3300/graphql`

**Now just have fun with the querys**

