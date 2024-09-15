# Books REST API

A Spring Boot-based REST API for managing books.

## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)

## Features

- Create and update books
- Retrieve book information
- List all books
- Delete books

## Technologies

- Java 21
- Spring Boot 3.3.3
- Spring Data JPA
- H2 Database (in-memory)
- Maven
- JUnit 5
- Lombok

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 21
- Maven 3.6+

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/books-rest-api.git
   ```

2. Navigate to the project directory:
   ```
   cd books-rest-api
   ```

3. Build the project:
   ```
   ./mvnw clean install
   ```

## Usage

Run the application using Maven:

```
./mvnw spring-boot:run
```

The API will be available at `http://localhost:8080`.

## API Endpoints

- `PUT /books/{isbn}` - Create or update a book
- `GET /books/{isbn}` - Retrieve a book by ISBN
- `GET /books` - List all books
- `DELETE /books/{isbn}` - Delete a book by ISBN

For detailed information about request/response formats, please refer to the API documentation.

## Testing

Run the tests using Maven:

```
./mvnw test
```
