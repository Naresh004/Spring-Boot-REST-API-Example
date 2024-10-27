# Spring-Boot-REST-API-Example
This repository contains a Spring Boot application that demonstrates how to create a RESTful web service using Spring Data JPA. The application manages users and their posts, providing full CRUD operations with custom exception handling, data filtering, and internationalization support, basic security configurations.


This project is a RESTful web service built with Spring Boot. It includes user management, post management, and various other features like internationalization, filtering, and security.

## Features

- User CRUD operations
- Post management for users
- Custom exception handling
- Data filtering
- Internationalization
- Basic security configuration

## Technologies Used

- Java
- Spring Boot
- Spring Data JPA
- Spring Security
- H2 Database (can be easily switched to other databases)

## Getting Started

### Prerequisites

- Java JDK 11 or later
- Maven

### Running the Application

1. Clone the repository:
2. Navigate to the project directory:
3. Run the application :


The application will start running at `http://localhost:8080`.

## API Endpoints

- `GET /users`: Retrieve all users
- `GET /users/{id}`: Retrieve a specific user
- `POST /users`: Create a new user
- `DELETE /users/{id}`: Delete a user
- `GET /users/{id}/posts`: Retrieve posts for a specific user
- `POST /users/{id}/posts`: Create a post for a specific user

## Security

The application uses basic authentication. You can configure users in the `SpringSecurityConfiguration` class.

## Internationalization

The application supports internationalization. You can add more languages by creating new properties files in the `resources` folder.
