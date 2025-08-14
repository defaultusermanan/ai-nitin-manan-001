# Architecture Overview

## Application Structure

The project is a simple Node.js application with the following structure:

- `index.js`: The main entry point of the application. It creates an HTTP server using Node.js' built-in `http` module.

## How It Works

1. The `http.createServer` method is used to create an HTTP server.
2. The server listens on port `3000`.
3. When a request is received, the server responds with a status code of `200` and the message "Hello, World!".

## CodeQL Workflow

The repository includes a CodeQL workflow located in `.github/workflows/`. This workflow is used to analyze the code for potential security vulnerabilities and ensure code quality.
