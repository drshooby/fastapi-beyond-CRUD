# FastAPI Beyond CRUD 

This is the source code for the [FastAPI Beyond CRUD](https://youtube.com/playlist?list=PLEt8Tae2spYnHy378vMlPH--87cfeh33P&si=rl-08ktaRjcm2aIQ) course. The course focuses on FastAPI development concepts that go beyond the basic CRUD operations.

For more details, visit the project's [website](https://jod35.github.io/fastapi-beyond-crud-docs/site/).

- This fork uses an Actions workflow to ensure commit convention is followed on PRs. Additionally, nightly builds are automatically uploaded to Docker Hub at midnight PST, assuming all tests are passed.

## Table of Contents

1. [Getting Started](#getting-started)
2. [Prerequisites](#prerequisites)
3. [Project Setup and Startup](#project-setup-and-startup)
5. [Running Tests](#running-tests)
6. [Documentation](#documentation)
7. [Contributing](#contributing)

## Getting Started
Follow the instructions below to set up and run your FastAPI project.

### Prerequisites
Ensure you have the following installed:

- Docker, Docker Desktop (preferred)

### Project Setup and Startup
1. Clone the project repository:
    ```bash
    https://github.com/drshooby/fastapi-beyond-CRUD.git
    ```
   
2. Navigate to the project directory:
    ```bash
    cd fastapi-beyond-CRUD/
    ```

3. Set up environment variables by copying the example configuration:
    ```bash
    cp .env.example .env
    ```

4. Run Docker Compose Up:
    ```bash
    docker compose up -d
    ```

### Running Tests
    - Tests can be run from within the Docker container using pytest

### Documentation
    - After startup, find documentation at http://localhost:8000/api/v1/docs and http://localhost:8000/api/v1/redoc

## Contributing
I welcome contributions to improve the documentation! You can contribute [here](https://github.com/jod35/fastapi-beyond-crud-docs).
