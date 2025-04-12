# Debugging API Backend

This repository contains the backend service for the API Debugger tool built with **Spring Boot**. It supports multiple HTTP methods, including `GET`, `POST`, `PUT`, and `DELETE`, and is designed to be used in conjunction with the frontend UI to test API calls.

## Features

- Handle API requests with methods: `GET`, `POST`, `PUT`, and `DELETE`.
- Responds with a simple message for `GET` and a greeting for `POST`/`PUT`.
- Provides a mock `DELETE` functionality to simulate user deletion.

## Installation

### Prerequisites
- **Java 11+** (Java Development Kit)
- **Maven** (to build and run the project)

### Steps to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/gargi790/debug-api-backend.git
   cd debug-api-backend
