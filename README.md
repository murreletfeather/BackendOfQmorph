# Qmorph Backend Service

This is the backend service for the Qmorph project, built with Spring Boot.

## Prerequisites

- Java 21 or higher
- Maven 3.6 or higher

## Project Structure

```
src/
├── main/
│   ├── java/
│   │   └── com/
│   │       └── qmorph/
│   │           └── backend/
│   │               ├── config/
│   │               ├── controller/
│   │               ├── model/
│   │               ├── repository/
│   │               ├── service/
│   │               └── QmorphBackendApplication.java
│   └── resources/
│       └── application.properties
```

## Getting Started

1. Clone the repository
2. Navigate to the project directory
3. Run the application:
   ```bash
   mvn spring-boot:run
   ```

The application will start on port 8080.

## Features

- RESTful API endpoints
- H2 in-memory database
- JPA/Hibernate ORM
- Spring Boot DevTools for development
- Lombok for reducing boilerplate code

## API Documentation

API documentation will be available at `http://localhost:8080/swagger-ui.html` once implemented.

## Database

The project uses H2 in-memory database for development. The H2 console is available at:
`http://localhost:8080/h2-console`

Default credentials:
- JDBC URL: `jdbc:h2:mem:qmorphdb`
- Username: `sa`
- Password: `password`