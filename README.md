# Food Delivery Management System

A backend application developed using Java and Spring Boot to manage food ordering and delivery operations.

## Project Overview

The Food Delivery Management System provides REST APIs for managing users, restaurants, food items, customer orders, and delivery partner assignments.

## Technologies Used

- Java 21
- Spring Boot
- Spring Data JPA
- Spring Security
- MySQL
- Maven
- REST APIs
- Postman

## Features

- User registration with BCrypt password encryption
- Login credential validation
- Restaurant management
- Food item management
- View available food items
- Customer food ordering
- Order status management
- Delivery partner assignment

## User Roles

- ADMIN
- CUSTOMER
- DELIVERY_PARTNER

## Order Status

- PLACED
- PREPARING
- OUT_OF_DELIVERY
- DELIVERED

## Database Configuration

1. Create a MySQL database named `foodd`.
2. Configure your database connection in `application.properties`.
3. Add your own MySQL username and password locally.
4. Run the Spring Boot application.

Do not commit database passwords or private credentials to GitHub.

## How to Run the Project

1. Clone this repository.
2. Open the project in Eclipse or Spring Tool Suite.
3. Configure MySQL database credentials.
4. Update Maven dependencies.
5. Run the main Spring Boot application.
6. Test the REST APIs using Postman.

## Project Type

Backend Development | REST API Application

## Author

Karthika N.
