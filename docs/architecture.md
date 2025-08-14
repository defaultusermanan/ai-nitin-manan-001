# Architecture Overview

## Project Structure

```
.
├── README.md       # Project description
├── index.js        # Main application file
```

### Key Components

1. **index.js**
   - This is the entry point of the application.
   - It creates an HTTP server using Node.js's built-in `http` module.
   - The server listens on port `3000` and responds with "Hello, World!" to all incoming requests.

### Workflow

- The server is started by running `node index.js`.
- Once running, it listens for HTTP requests and responds with a plain text message.

---

For setup instructions, see the [Getting Started](getting-started.md) page.