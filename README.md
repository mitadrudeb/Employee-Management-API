Employee-Management-System

The Employee Management System is a Java-based web application designed to manage employee information efficiently. It provides functionality to perform CRUD (Create, Read, Update, Delete) operations on employee data. This project is built using Java, Spring Boot, Maven, and follows the Model-View-Controller (MVC) architecture pattern.

This repository contains all the source code and SQL scripts needed to run the application locally or deploy it in a production environment.

Features
•	Employee CRUD operations: Add, view, update, and delete employee records.
•	Database integration: Uses MySQL to store employee information.
•	RESTful API: The application exposes REST endpoints for seamless integration with other systems.
•	Maven project: Built using Maven for easy dependency management and project configuration.
•	Spring Boot framework: Simplifies application development with Spring Boot's dependency injection and autoconfiguration.

Technologies Used
•	Java: Core language for the application logic.
•	Spring Boot: Framework used for building the application.
•	Maven: For project build and dependency management.
•	MySQL: Database for storing employee data.
•	Thymeleaf: Templating engine for rendering views.
•	Hibernate: ORM for interacting with the database.
•	Git: Version control for the project.


Getting Started

Prerequisites
•	Java 8 or higher
•	Maven 3.6 or higher

Installation
1.	Clone the repository: 
git clone https://github.com/mitadrudeb/Employee-Management-System.git
2.	Navigate to the project directory: 
cd Employee-Management-System
3.	Build the project using Maven: 
mvn clean install
4.	Run the application: 
mvn spring-boot:run

API Endpoints
The application provides the following RESTful endpoints for managing employees:
•	GET /employees: List all employees.
•	GET /employees/{id}: Get details of a specific employee.
•	POST /employees: Add a new employee.
•	PUT /employees/{id}: Update an existing employee.
•	DELETE /employees/{id}: Delete an employee.

Testing
Run the tests using Maven:
mvn test


