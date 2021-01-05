# ✨ Laravel GraphQL ✨
To learn a little about **GraphQL**, i made a simple project that makes the relationship between users and posts with content and title, and here's what I did

## 🚀 Installation 🚀

It's very simple you just need to have the **docker** and **docker-compose** installed.<br/>
With that installed just run the following command

```shell
 $ docker-compose up -d
```
You will already have the PHPMyAdmin environment to orchestrate your bank, access URL <br/>
`http://localhost:9001`

## 👷 Usage 👷

To test you will need an environment to test HTTP calls.<br/>
My indications:
- Altair (Linux tool)
- GraphQL Playground (Extension chrome, or install in your computer)

In your environment access the route <br/>
`http://localhost:3300/graphql`

## 📌 Database 📌

**Two tables were created, using MySQL, one that shows users, and the other that shows posts, the content of each table is:**

| users |  posts  |
|:-----:|:-------:|
|  name |  author |
| email |  title  |
|       | content |

```
:exclamation: The relationships between them occur in the author, who uses the id of each user who generates a post
```
