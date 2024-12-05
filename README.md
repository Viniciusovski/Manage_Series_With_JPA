# 📺 Manage Series With JPA

Welcome to the **Manage Series With JPA** project repository! This project uses **Spring Data JPA** to map classes to the database with **ORM**, manage relationships between entities, and integrate with the **ChatGPT API**.

## 📋 Description

This project is designed to manage TV series, allowing users to add and view series information. It also integrates with the ChatGPT API to provide detailed descriptions and recommendations.

## 🚀 Features

- **Series Management**: Add, update, delete, and view series.
- **ORM Mapping**: Use Spring Data JPA to map Java classes to database tables.
- **Entity Relationships**: Configure one-to-many and many-to-many relationships between entities.
- **ChatGPT Integration**: Connect to the ChatGPT API for automated descriptions and recommendations.

## 🛠️ Technologies

- **Java 11**
- **Spring Boot**
- **Spring Data JPA**
- **Hibernate**
- **MySQL/PostgreSQL** (or other relational database)
- **ChatGPT API**

## 🏗️ Project Structure

```plaintext
src/
│
├── main/
│   ├── java/
│   │   └── com/
│   │       └── example/
│   │           └── series/
│   │               ├── controller/
│   │               ├── model/
│   │               ├── repository/
│   │               ├── service/
│   │               └── ChatGPTIntegration.java
│   ├── resources/
│   │   ├── application.properties
│   │   └── data.sql
│   └── webapp/
│       └── static/
│
└── test/
    └── java/
        └── com/
            └── example/
                └── series/
