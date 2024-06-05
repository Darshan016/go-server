# Simple Go Web Server

This is a simple web server implemented in Go. It serves static files from the `static` directory and provides two additional endpoints: `/hello` and `/form`.


## Getting Started

### Prerequisites

- Go (version 1.16 or later)

### Running the Server

1. Clone the repository or download the files to your local machine.

2. Navigate to the project directory.

3. Run the server:

    ```sh
    go run main.go
    ```

4. Open your web browser and go to `http://localhost:8080` to see the static website.

### Endpoints

- `/`: Serves static files from the `static` directory.
- `/hello`: Returns a simple "hello" message.
- `/form`: Handles form submissions and echoes the submitted name and city.

### Example

1. Open `http://localhost:8080` to view the `index.html` file.
2. Navigate to `http://localhost:8080/hello` to see the "hello" message.
3. Submit a POST request to `http://localhost:8080/form.html` with form data:
    - `name`: Your name
    - `city`: Your city

Feel free to contribute!