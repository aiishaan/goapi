# Simple Go API with Authentication

This is a simple API built using Go that includes authentication. The API utilizes token-based authentication to secure access to its endpoints,


## Requirements

- Go 1.18+
- A PostgreSQL or SQL-based database (optional, based on your setup)

## Getting Started

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/go-simple-api.git
    cd go-simple-api
    ```

2. Install dependencies:

    ```bash
    go mod tidy
    ```

3. Set up environment variables (e.g., database connection string, JWT secret):

    ```bash
    export DB_CONNECTION_STRING="your_database_connection_string"
    export JWT_SECRET="your_jwt_secret"
    ```

4. Run the application:

    ```bash
    go run main.go
    ```


