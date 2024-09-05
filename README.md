# Employee Management System

The Employee Management System is a Java-based web application designed to manage employee information efficiently. It provides functionality to perform CRUD (Create, Read, Update, Delete) operations on employee data. This project is built using Java, Spring Boot, and Maven, following the Model-View-Controller (MVC) architecture pattern.

This repository contains all the source code and SQL scripts needed to run the application locally or deploy it in a production environment.

### Features

1.	Employee CRUD operations: Add, view, update, and delete employee records.

2.	Database integration: Uses MySQL to store employee information.

3.	RESTful API: Exposes REST endpoints for seamless integration with other systems.

4.	Maven project: Built using Maven for easy dependency management and project configuration.

5.	Spring Boot framework: Simplifies application development with dependency injection and autoconfiguration.


### Technologies Used

1.	Java: Core language for the application logic.    
2.	Spring Boot: Framework for building the application.   
3.	Maven: For project build and dependency management.
4.	MySQL: Database for storing employee data.
5.	Thymeleaf: Templating engine for rendering views.
6.	Hibernate: ORM for interacting with the database.
7.	Git: Version control for the project.


## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

1.	Java 8 or higher
2.	Maven 3.6 or higher
3.	MySQL (or any relational database)

### Installation

Follow these steps to set up the project locally:

Clone the repository:

    git clone https://github.com/mitadrudeb/Employee-Management-System.git

Navigate to the project directory:

    cd Employee-Management-System


Build the project using Maven:

    mvn clean install


Run the application:

    mvn spring-boot:run
    

## API Endpoints

The application exposes the following RESTful endpoints for managing employees:

    GET /employees: List all employees.
    
    GET /employees/{id}: Get details of a specific employee.
    
    POST /employees: Add a new employee.
    
    PUT /employees/{id}: Update an existing employee.
    
    DELETE /employees/{id}: Delete an employee.
    

## Testing

To run the tests, execute the following command:

    mvn test
