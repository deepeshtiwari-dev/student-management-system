# Student Management System

A RESTful Student Management System built using Java and Spring Boot.
The application provides CRUD operations for managing student records
using a MySQL database.

## Tech Stack

- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- MySQL
- Maven
- REST API

## Features

- Add a new student
- Retrieve all students
- Retrieve student details
- Update student information
- Delete a student
- Email uniqueness validation
- MySQL database integration
- RESTful API architecture

## Project Architecture

Controller → Service → Repository → MySQL

### Controller
Handles HTTP requests and exposes REST API endpoints.

### Service
Contains the business logic of the application.

### Repository
Uses Spring Data JPA to interact with the database.

### Entity
Represents the Student data stored in the MySQL database.

## CRUD Operations

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/v1/student` | Get all students |
| POST | `/api/v1/student` | Add a new student |
| PUT | `/api/v1/student/{id}` | Update student details |
| DELETE | `/api/v1/student/{id}` | Delete a student |

## Database

The original tutorial project used PostgreSQL.
The project was modified and configured to use **MySQL** as the database.

The application uses Spring Data JPA and Hibernate for database
interaction and persistence.

## How to Run

1. Clone the repository.
2. Create a MySQL database.
3. Configure the database credentials in `application.properties`.
4. Build the project using Maven.
5. Run the Spring Boot application.
6. Test the REST APIs using Postman or another API client.

## Learning Reference

This project was adapted from a Spring Boot CRUD tutorial by
Amigoscode.

The original tutorial was used as a learning reference, and the
project was subsequently customized and configured for MySQL-based
student management.

## Author

Deepesh Tiwari
