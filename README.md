# Simple Greeting API

This project demonstrates a simple RESTful web service built using Spring Boot and Test Driven Development (TDD) principles.

## What it does

The API provides a greeting endpoint that returns JSON responses:

- **Basic Greeting**: `GET /greeting` returns `{"content":"Hello, World!"}`
- **Custom Greeting**: `GET /greeting?name=User` returns `{"content":"Hello, User!"}`

## TDD Approach

This project was built using Test Driven Development:
1. Tests were written first to define the requirements
2. Code was implemented to satisfy the tests
3. The cycle was repeated for each feature

## Testing

Run tests with `./mvnw test`
