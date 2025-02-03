# Go-REST-API
This repository contains a **Go-based REST API** for managing user registrations and events. It provides endpoints for user login, registration, and event management.

## Technologies Used
- **Go**: The primary programming language.
- **Gorilla Mux**: A powerful HTTP router and URL matcher.
- **PostgreSQL**: A relational database for storing user and event data.

## Features
- User registration and cancellation
- Event creation and management
- Secure login functionality

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/go-rest-api.git
   ```
2. Navigate to the project directory:
   ```bash
   cd go-rest-api
   ```
3. Install dependencies:
   ```bash
   go mod tidy
   ```
4. Run the application:
   ```bash
   go run main.go
   ```

## Usage
The API provides the following HTTP endpoints:
- **POST /register**: Register a new user.
- **POST /login**: Authenticate a user.
- **POST /events**: Create a new event.
- **GET /events**: Retrieve all events.

Example HTTP requests can be found in the `/api-test` directory.

## Contributing
Contributions are welcome! If you'd like to contribute, please:
1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Submit a pull request with a detailed description of your changes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
