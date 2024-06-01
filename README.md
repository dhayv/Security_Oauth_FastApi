# FastAPI Authentication Project

This project implements an authentication system using FastAPI. It includes token-based authentication with JWTs, password hashing with `passlib`, and user management.

## Setup

1. Install the required dependencies:
    ```bash
    pip install fastapi uvicorn passlib[bcrypt] python-jose pydantic
    ```

2. Run the FastAPI application:
    ```bash
    uvicorn main:app --reload
    ```

## Configuration

To generate a secret key for JWT, run:
```bash
openssl rand -hex 32
