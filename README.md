<img src="assets/laravel-lighthouse.png" alt="table and columns from each" style="float: left; width: 10px; height:10px; text-align: center"/>
![](assets/laravel-lighthouse.png)

# Laravel GraphQL
To learn a little about GraphQL, I made a simple project that makes the relationship between users and posts with content and title, and here's what I did

## What was done ?!
[!][MYSQL Version][mysql-image]

Two tables were created, using MySQL, one that shows users and the other that shows posts, the content of each table is:

| users |  posts  |
|:-----:|:-------:|
|  name |  author |
| email |  title  |
|       | content |

```
The relationships between them occur in the author, 
who uses the id of each user who generates a post
```



