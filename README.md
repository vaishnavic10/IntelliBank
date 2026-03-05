IntelliBank – Banking Management System
Overview

IntelliBank is a secure Banking Management System built using Core Java, JDBC, SQL, and JWT authentication. The application allows users to perform basic banking operations such as account creation, deposits, withdrawals, and transaction tracking while ensuring secure authentication and database management.

The project demonstrates object-oriented programming, database connectivity, and secure authentication practices used in backend banking applications.

Features

User registration and secure login

JWT-based authentication for secure access

Create and manage bank accounts

Deposit and withdraw money

View account balance

Transaction history tracking

Secure database storage using SQL

Data handling using JDBC connectivity

Tech Stack

Programming Language: Core Java

Database Connectivity: JDBC

Database: MySQL / SQL

Authentication: JSON Web Token (JWT)

Concepts Used: OOP, Exception Handling, File Handling, Secure Session Management

System Architecture

The application follows a modular architecture where different components handle authentication, banking operations, and database interaction.

Modules:

Authentication Module (JWT login & validation)

Account Management Module

Transaction Module

Database Connectivity Module (JDBC)

Project Structure
IntelliBank/
│
├── src/
│   ├── auth/
│   │   └── JWTAuthentication.java
│   │
│   ├── database/
│   │   └── DBConnection.java
│   │
│   ├── model/
│   │   └── Account.java
│   │
│   ├── service/
│   │   ├── AccountService.java
│   │   └── TransactionService.java
│   │
│   └── IntelliBankApp.java
│
├── database/
│   └── bank_schema.sql
│
└── README.md
Database Tables

Example tables used in the system:

Users Table

user_id

username

password

role

Accounts Table

account_id

user_id

account_type

balance

Transactions Table

transaction_id

account_id

type

amount

date

How to Run the Project

Clone the repository

git clone https://github.com/yourusername/intellibank.git

Import the project into your IDE (IntelliJ / Eclipse / VS Code).

Set up the SQL database and run the schema file.

Configure database credentials in the DBConnection.java file.

Compile and run the main application file:

IntelliBankApp.java
Future Enhancements

Web-based interface using Spring Boot

OTP-based authentication

Loan and investment modules

Admin dashboard for bank employees

REST API integration

Author

Vaishnavi Chopade
Software Engineer | Java Backend Developer | MERN Stack

⭐ If you like this project, consider giving it a star!



