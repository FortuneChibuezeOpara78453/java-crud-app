# Lab 1: Git Basics - Java CRUD Application with Vaadin

This repository contains a simple Java CRUD (Create, Read, Update, Delete) web application built using Spring Boot, Spring Data JPA, H2 In-Memory Database, and Vaadin.

Developed for **Laboratory 1 – Git Basics**.

## Tech Stack
- **Java 21**
- **Spring Boot 4 / 3**
- **Spring Data JPA & H2 Database**
- **Vaadin 25**
- **Maven** (with Maven Wrapper `./mvnw`)

## Running the Application Locally

To start the application, open a terminal in the project directory and run:

### Windows (PowerShell or CMD):
```powershell
.\mvnw.cmd spring-boot:run
```

### Linux / macOS:
```bash
./mvnw spring-boot:run
```

Once started, open your web browser and navigate to:
```
http://localhost:8080
```

## Features
- **List Customers**: View all customer records in an interactive grid.
- **Filter Customers**: Filter customers by last name using the search bar.
- **Add Customer**: Click "+ New customer" to add a new record.
- **Edit / Delete Customer**: Click any row in the grid to edit the details or delete the record.

## Documentation
Screenshots of the running application, CRUD operations, and startup logs are located in the [`doc/`](doc/) directory.
