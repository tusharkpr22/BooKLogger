# Inventory Management System

## Overview

The Inventory Management System is a comprehensive web application designed to manage products, users, and inventory operations efficiently. Built using Java and the Spring Boot framework, the system provides an intuitive interface for administrators and users to interact with the inventory.

---

## Features

- **User Management**: Register, login, and manage user accounts.
- **Product Management**: Add, update, delete, and view product details.
- **Role-Based Access**: Different functionalities for administrators and regular users.
- **Responsive UI**: Designed with HTML, CSS, and static resources for a user-friendly experience.

---

## Technology Stack

### Backend:

- Java (Spring Boot Framework)
- Maven (Build Tool)
- JPA (Java Persistence API)

### Frontend:

- HTML/CSS for templates
- Static resources (images, CSS files)

### Database:

- H2 Database (for development, configurable for production)

---

## Project Structure

### Key Directories

- **`src/main/java`**: Contains the Java source code for the application.

  - `controllers/`: REST controllers for handling requests.
  - `entities/`: Entity classes mapped to database tables.
  - `repositories/`: Interfaces for database operations.
  - `services/`: Business logic implementation.

- **`src/main/resources`**:

  - `static/`: Frontend assets (CSS, images, etc.).
  - `templates/`: Thymeleaf templates for views.
  - `application.properties`: Configuration file for the application.

- **`src/test/java`**: Contains test cases for the application.

- **`target/`**: Generated files after compilation and build.

---

## Prerequisites

### Tools Required:

- **Java Development Kit (JDK)**: Version 17 or above
- **Maven**: Version 3.6 or above
- **IDE**: IntelliJ IDEA, Eclipse, or any Java IDE

---

## Installation and Setup

1. **Clone the Repository**:

   ```bash
   git clone <repository-url>
   cd Inventory_Management_System
   ```

2. **Build the Project**:

   ```bash
   mvn clean install
   ```

3. **Run the Application**:

   ```bash
   mvn spring-boot:run
   ```

4. **Access the Application**:
   Open your browser and navigate to:

   ```
   ```

[http://localhost:8080](http://localhost:8080)

````

---

## Configuration

### Update `application.properties`:
Modify the database configuration if needed:
```properties
spring.datasource.url=jdbc:h2:mem:testdb
spring.datasource.username=your-username
spring.datasource.password=your-password
````

---

## Contribution Guidelines

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes and push to the branch:
   ```bash
   git push origin feature-name
   ```
4. Open a pull request.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Contact

For any queries or contributions, reach out to the project maintainers via email or open an issue in the repository.

dashgautam331\@gmail.com


