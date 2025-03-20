# Code Kata: Simple HTTP Request Handler

## Objective
Create a lightweight HTTP server that receives and processes incoming requests with different endpoints and response types.

## Requirements
1. Build a basic HTTP server that:
   - Listens on a port (e.g., 3000)
   - Handles at least 3 different routes/endpoints
   - Processes GET and POST requests
   - Returns appropriate responses in multiple formats (JSON, plain text)

2. Implement the following endpoints:
   - `/ping`: Returns a simple "pong" response with timestamp
   - `/echo`: Echoes back any data sent in a POST request
   - `/data`: Returns a JSON response with some mock data

3. Bonus functionality:
   - Implement basic request logging
   - Add simple error handling for invalid routes
   - Include a query parameter handler for one of the endpoints

## Constraints
- Use a server-side language of your choice (Node.js, Python, Ruby, Go, etc.)
- Don't use full web frameworks - focus on using just the HTTP server modules
- Implement proper HTTP status codes for different scenarios

## Learning Focus
- Creating an HTTP server from lightweight libraries
- Handling different HTTP methods (GET, POST)
- Parsing request data (body, query parameters, headers)
- Formulating proper HTTP responses
- Working with different content types

## Example Usage
```
$ curl http://localhost:3000/ping
Pong! Server time: 2025-03-21 14:25:30

$ curl -X POST -d "message=hello world" http://localhost:3000/echo
{"received":"hello world"}

$ curl http://localhost:3000/data
{"items":[{"id":1,"name":"Item 1"},{"id":2,"name":"Item 2"}]}

$ curl http://localhost:3000/invalid
404: Not Found
```

This kata focuses on receiving and processing network requests, giving you practice with the server-side handling of HTTP communication. It's sized appropriately for a single practice session while still covering important concepts in backend web development.
