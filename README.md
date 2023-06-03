# A RESTful Web Service API with Go and Gin

This project demonstrates the basics of writing a RESTful web service API with Go and the [Gin Web Framework](https://gin-gonic.com/docs/) (Gin). To keep things simple, I stored data in memory. A more typical API would interact with a database.

## Prerequisites

To get started, you need to have the following installed on your system:

- Go (version 1.17 or later)
- Git

You can check the installed versions using the following commands:

```bash
go version
git --version
```

## Installation

1. First, clone the repository to your local machine

2. Navigate to the cloned repository

3. Install the required dependencies
```bash
go get .
```

4. Running the Application
```bash
go run .
```

The server will start at `http://localhost:8080`. You can test the different endpoints using a tool like Postman, curl or simply your web browser.