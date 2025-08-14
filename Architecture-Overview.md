# Architecture Overview

This project is a minimal Node.js application designed to demonstrate the basics of an HTTP server. Below is an overview of its architecture.

## Core Components

### 1. **HTTP Server**
The server is implemented using Node.js's built-in `http` module. It listens on port `3000` and responds with a plain text message "Hello, World!".

#### Code Snippet:
```javascript
const http = require('http');

const server = http.createServer((req, res) => {
  res.statusCode = 200;
  res.setHeader('Content-Type', 'text/plain');
  res.end('Hello, World!\n');
});

const PORT = 3000;
server.listen(PORT, () => {
  console.log(`Server running at http://localhost:${PORT}/`);
});
```

### 2. **CodeQL Workflow**
The repository includes a CodeQL workflow for security analysis. This ensures that the code is analyzed for vulnerabilities and adheres to best practices.

## Design Philosophy

- **Simplicity:** The project is intentionally minimal to focus on the core functionality of an HTTP server.
- **Extensibility:** While simple, the project can be extended to include additional routes, middleware, or integrate with a database.