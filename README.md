# Go URL Shortener

A simple URL shortener written in Go.

## Features
- Generate short URLs for long links.
- Redirect short URLs to their original links.
- RESTful API implementation.

## Endpoints
- **GET /**: Root endpoint to verify server is running.
- **POST /shorten**: Create a short URL.
- **GET /redirect/{shortURL}**: Redirect to the original URL.

## Running the Project
1. Install Go.
2. Run the server:
   ```bash
   go run main.go
