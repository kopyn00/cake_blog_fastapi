# Cake Blog FastAPI

A cake baking blog application built with **FastAPI**, **SQLAlchemy**, and **Jinja2**.

The project started as a learning project inspired by [Corey Schafer's FastAPI Full Course](https://github.com/CoreyMSchafer/FastAPI-Full-Course/).

The original tutorial provided the foundation for learning FastAPI. Since then, I have extended the application with additional features, backend functionality, database integration, and automated tests.

## Technologies

- **Python**
- **FastAPI** - Backend framework
- **SQLAlchemy** - ORM and database integration
- **Pydantic** - Data validation
- **PostgreSQL** - Database
- **Alembic** - Database migrations
- **Jinja2** - Server-side rendering
- **AWS S3** - Image storage
- **Boto3** - AWS SDK
- **HTML / CSS / JavaScript**
- **Pytest** - Automated testing
- **HTTPX** - API testing
- **Moto** - AWS service mocking

## Features

- User registration and authentication
- JWT-based authorization
- Password hashing
- Password reset via email
- User profile management
- Profile picture uploads using AWS S3
- Blog post creation, editing, and deletion
- Post pagination
- Likes and dislikes
- Server-side rendered pages with Jinja2
- Database migrations with Alembic
- Automated API and integration tests

## Testing

The project uses pytest for automated testing.

The test suite includes:

- API endpoint tests
- User registration and authentication tests
- Post CRUD tests
- Database integration tests using PostgreSQL
- AWS S3 tests using Moto
- Asynchronous tests using AnyIO and HTTPX

Run tests with:

```bash
pytest -v
```

## Project Goals

- Develop backend development skills with FastAPI.
- Practice REST API design and implementation.
- Work with relational databases and SQLAlchemy.
- Implement authentication and authorization.
- Understand cloud storage integration.
- Write automated tests for backend applications.

## Acknowledgements

Special thanks to [Corey Schafer](https://github.com/CoreyMSchafer) for creating the FastAPI course that inspired this project.

Original course: [FastAPI Full Course](https://github.com/CoreyMSchafer/FastAPI-Full-Course/)

---

*This is a personal learning project and is still under development.*