# FastAPI Project

A personal project focused on building web APIs using FastAPI and Python.

FastAPI is a modern Python web framework designed for building high-performance APIs with automatic data validation, type hints, and interactive API documentation.

This project provides an opportunity to explore backend development, API design, request handling, and data validation using FastAPI.

## Project Objectives

- Build RESTful APIs using Python.
- Understand HTTP methods and status codes.
- Handle path parameters, query parameters, and request bodies.
- Validate incoming data using Pydantic.
- Explore API documentation with Swagger UI.
- Practice backend development and API testing.

## Technologies Used

- Python
- FastAPI
- Uvicorn
- Pydantic

## Getting Started

### Prerequisites

- Python installed on your system
- Basic knowledge of Python and HTTP
- Git installed on your system

### Installation

Clone the repository:

```bash
git clone https://github.com/AVA999-op/fast_api.git
```

Navigate to the project directory:

```bash
cd fast_api
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate the virtual environment.

Windows:

```bash
venv\Scripts\activate
```

Linux and macOS:

```bash
source venv/bin/activate
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

## Running the Application

If the main application instance is defined as `app` inside `main.py`, start the development server with:

```bash
uvicorn main:app --reload
```

Open the following URL in your browser:

http://127.0.0.1:8000

### Interactive API Documentation

FastAPI automatically generates interactive API documentation.

- Swagger UI: http://127.0.0.1:8000/docs
- ReDoc: http://127.0.0.1:8000/redoc

These interfaces allow you to explore available endpoints and test API requests.

## Core Concepts

### API Endpoints

Define routes that handle incoming HTTP requests and return responses.

### Request Validation

Use Pydantic models to validate request data and define expected data structures.

### HTTP Methods

Work with common HTTP methods, including:

- `GET` — Retrieve data
- `POST` — Create or submit data
- `PUT` — Replace existing data
- `PATCH` — Partially update data
- `DELETE` — Remove data

### Automatic Documentation

Generate interactive API documentation from application routes, parameters, and schemas.

## Future Improvements

- Add database integration.
- Implement authentication and authorization where needed.
- Improve exception handling and response validation.
- Add automated tests.
- Organize endpoints into separate routers.
- Explore deployment and production configuration.

## Author

AVA999-op

GitHub: [@AVA999-op](https://github.com/AVA999-op)

## License

Please refer to the repository's license file for information about usage, modification, and distribution.
