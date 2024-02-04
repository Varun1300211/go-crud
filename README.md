# Go Movie CRUD Application

This is a simple CRUD (Create, Read, Update, Delete) backend application for managing movies. It is built using Go and utilizes the Gorilla Mux router.

## Features

- **Create:** Add new movies to the collection.
- **Read:** Retrieve information about all movies or a specific movie by ID.
- **Update:** Modify details of existing movies.
- **Delete:** Remove movies from the collection.

## Prerequisites

Before running the application, make sure you have the following installed:

- Go (at least version 1.11)
- Gorilla Mux: `go get -u github.com/gorilla/mux`

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/go-movie-crud.git
    cd go-movie-crud
    ```

2. Initialize the Go module and install dependencies:

    ```bash
    go mod init go-movie-crud
    go get -u github.com/gorilla/mux
    ```

3. Run the application:

    ```bash
    go run main.go
    ```

    The server will start at `http://localhost:8000`.

## API Endpoints

- **GET /movies:** Get a list of all movies.
- **GET /movies/{id}:** Get details of a specific movie by ID.
- **POST /movies:** Create a new movie.
- **PUT /movies/{id}:** Update details of a specific movie by ID.
- **DELETE /movies/{id}:** Delete a movie by ID.