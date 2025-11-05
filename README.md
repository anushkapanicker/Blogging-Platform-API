# ☕ Blogging Platform API

A simple RESTful API built with **Spring Boot** that supports CRUD operations for blog posts.

## 🚀 Features
- Create, Read, Update, Delete blog posts
- Search posts by title, content, or category
- In-memory H2 Database
- Tested with Postman

## ⚙️ Tech Stack
- Java 17+
- Spring Boot
- H2 Database
- Maven
- IntelliJ IDEA

## 🧩 Endpoints

| Method | Endpoint | Description |
|--------|-----------|-------------|
| POST | `/posts` | Create a new blog post |
| GET | `/posts` | Get all posts |
| GET | `/posts/{id}` | Get post by ID |
| PUT | `/posts/{id}` | Update post |
| DELETE | `/posts/{id}` | Delete post |
| GET | `/posts?term={keyword}` | Search posts |

## 🗃️ Database Console
Visit: [http://localhost:8080/h2-console](http://localhost:8080/h2-console)  
JDBC URL: `jdbc:h2:mem:blogdb`  
User: `sa`  
Password: *(leave blank)*

#### 💻 Note: All URLs are for local development. The app runs on `localhost:8080` by default.

## 🌐 Project URL
https://roadmap.sh/projects/blogging-platform-api

## 🧠 Run the Project
```bash
mvn spring-boot:run

