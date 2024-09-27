# Go Web Server

## Overview

A simple Go web server that serves static files and handles basic form submissions. This project demonstrates basic routing, form handling, and serving static assets like HTML files.

## Features

- **Static File Serving:** Serve HTML, CSS, and JS files from the `/static` directory.
- **Routing:** Handles `/hello` and `/form` routes.
- **Form Handling:** Processes POST requests from an HTML form.

## Quick Start

### Prerequisites

- [Go](https://golang.org/doc/install) (v1.16 or later)

### Setup

1. Clone the repository:
   ```bash
   git clone git@github.com:Vaibhav701161/Go-Web-Server.git
   cd Go-Web-Server
   ```

2. Run the server:
   ```bash
   go run main.go
   ```

3. Open your browser and visit:
   - `http://localhost:8080/static/index.html` for the static page.
   - `http://localhost:8080/hello` for the greeting message.
   - Submit the form at `http://localhost:8080/static/form.html`.

## Project Structure

```bash
.
├── main.go          # Go server code
├── go.mod           # Go module file
├── static/          # Static HTML files
│   ├── index.html   # Homepage
│   └── form.html    # Form for user input
└── README.md        # Project documentation
```

