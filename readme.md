readme.md# Recipe REST API

This project is a simple REST API for managing recipes. It's built with Python and Django, containerized using Docker, and includes Swagger documentation.

## Features

- **Recipes Management**: Create, retrieve, update, and delete recipes.
- **User Authentication**: Secure API endpoints with user authentication.
- **Swagger Documentation**: Explore and test the API endpoints using Swagger UI.
- **TDD Approach**: Implemented using Test-Driven Development principles.
- **Code Quality**: Ensured using flake8 for linting and code consistency.

## Installation

1. **Clone Repository**:

    ```bash
    git clone https://github.com/yourusername/recipe-rest-api.git
    cd recipe-rest-api
    ```

2. **Build and Run with Docker**:

    ```bash
    docker-compose up --build
    ```

    The application will be available at `http://localhost:8000`.

## Usage

- **API Endpoints**: Explore the API using Swagger UI at `http://localhost:8000/swagger`.
- **Authentication**: Use the provided endpoints for user signup and login to access protected routes.

## Development

- **Requirements**: Ensure you have Docker installed.
- **Local Development**: Edit code locally and rebuild the Docker container as needed.
- **Test-Driven Development**: Write tests following the TDD approach for each feature or functionality.
- **Code Quality**: Use flake8 for linting and maintaining code consistency.

## Contributing

Contributions are welcome! Please feel free to open issues or submit pull requests for any improvements or additional features.

## License

This project is licensed under the [MIT License](LICENSE).
