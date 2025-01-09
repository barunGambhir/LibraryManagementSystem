# Library Management System

A full-fledged **Library Management System** built with **Spring Boot**. This application allows users to manage books, authors, categories, and publishers. It provides functionalities like adding, editing, deleting, and viewing details for each entity. The dynamic HTML views are rendered using Thymeleaf.

---

## Features

- Manage books, authors, categories, and publishers.
- CRUD operations for all entities.
- Relationships between entities like Many-to-Many (Books ↔ Authors, Books ↔ Categories, etc.).
- Dynamic web pages using Thymeleaf.
- Preloaded sample data for testing and demonstration purposes.

---

## Tech Stack

### Backend:
- **Spring Boot 2.5.4**
- **Spring Data JPA** (for database interaction)
- **H2 Database** (in-memory database for testing and development)

### Frontend:
- **Thymeleaf** (for rendering dynamic HTML templates)

### Other Tools:
- **Lombok** (to reduce boilerplate code)
- **Maven** (for dependency management)

---

## Prerequisites

Before running the project, ensure you have the following installed:
1. **Java Development Kit (JDK) 11**
2. **Maven**
3. **Git**

---

## Setup and Running the Application

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/barunGambhir/LibraryManagementSystem.git
   cd LibraryManagementSystem
2. **Build the Project**: Run the following command to compile the project and download dependencies:

    ```bash
    mvn clean install

3. **Run the Application**: Use the Spring Boot Maven plugin to start the application:

    ```bash
    mvn spring-boot:run

## Contributing
Feel free to fork this repository and submit pull requests for any enhancements or bug fixes. Contributions are always welcome!

