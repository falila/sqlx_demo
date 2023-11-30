# Rust SQLx REST API Demo

This Rust project serves as a demonstration of utilizing the SQLx crate to implement a RESTful API with CRUD operations for managing User data.

## Prerequisites

Before running the project, ensure you have the following installed:

- Rust: [Install Rust](https://www.rust-lang.org/learn/get-started)
- SQLite: For simplicity, this demo uses SQLite as the database. You can install it via your package manager or download it from [SQLite website](https://www.sqlite.org/download.html).

## Setup

1. Clone this repository:

   ```bash
   git clone git@github.com:falila/sqlx_demo.git
   ```

2. Navigate to the project directory:

   ```bash
   cd sqlx_demo
   ```

3. Build and run the project:

   ```bash
   cargo run
   ```

## API Endpoints

The API provides the following endpoints for managing User data:

- **Create User:**

  `POST /users`

- **Get All Users:**

  `GET /users`

- **Get User by ID:**

  `GET /users/{id}`

- **Update User by ID:**

  `PUT /users/{id}`

- **Delete User by ID:**

  `DELETE /users/{id}`

## Example Usage

- **Create User:**

  ```bash
  curl -X POST -H "Content-Type: application/json" -d '{"name":"John Doe","email":"john@example.com"}' http://localhost:8080/users
  ```

- **Get All Users:**

  ```bash
  curl http://localhost:8080/users
  ```

- **Get User by ID:**

  ```bash
  curl http://localhost:8080/users/1
  ```

- **Update User by ID:**

  ```bash
  curl -X PUT -H "Content-Type: application/json" -d '{"name":"Updated Name","email":"updated@example.com"}' http://localhost:8080/users/1
  ```

- **Delete User by ID:**

  ```bash
  curl -X DELETE http://localhost:8080/users/1
  ```
