# Spring Boot Application
This application is built using the Spring Boot framework, simplifying Java-based application development.

## Description
A Simple Spring MVC app with no hypermedia. What is built is described as RPC (Remote Procedure Call).

It includes the following dependencies:
  - Web
  - JPA
  - H2
A simple payroll service that manages the employees of a company. It stores employee objects in a (H2 in-memory) database and accesses them via JPA.
Then it uses the Spring MVC as a web layer.

## Usage
Once the application is running, you can use the following endpoints to interact with the user data:

- `GET /employees`: Retrieve a list of all employees.
- `GET /employees/{id}`: Retrieve a specific employee by ID.
- `POST /employees`: Create a new employee.
- `PUT /employees/{id}`: Update an existing employee.
- `DELETE /employees/{id}`: Delete an employee by ID.