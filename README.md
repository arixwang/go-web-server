# Simple Go HTTP Server Example
This is a simple Go program that demonstrates the creation of an HTTP server using the net/http package. The program serves static files, handles a form submission, and responds to a basic "hello" endpoint.

## Features
1. **Static File Serving:** The program serves static files located in the ./static directory.
2. **Form Handling:** It handles a form submission at the /form endpoint. Upon receiving a POST request, the server parses the form data and responds with the submitted name and address.
3. **Hello Endpoint:** The /hello endpoint responds with a "hello!" message for GET requests.

## Usage
1. Clone repo
`git clone <repository-url>`
`cd <repository-directory>`
2. Run program
`go run main.go`
3. Access the server in your browser:
  - To view the static files, open your browser and navigate to http://localhost:8080.
  - To access the form, visit http://localhost:8080/form.
  - To receive a "hello!" response, visit http://localhost:8080/hello.

## Dependencies
This program uses the Go standard library and does not require any additional dependencies.

## File Structure
main.go: The main Go source code file containing the HTTP server implementation.
static/: A directory containing static files that will be served by the server.

