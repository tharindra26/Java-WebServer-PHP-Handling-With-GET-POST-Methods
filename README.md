# Java HTTP Server with PHP Support

This is a simple Java-based HTTP server that supports both GET and POST requests and can execute PHP files. You can use this server to serve HTML and PHP files, and it is designed to run on port 2728.

## Getting Started

### Prerequisites

1. **Prerequisites**: Ensure you have the following prerequisites installed:
    - Java Development Kit (JDK)
    - A web browser for testing

2. **Installation**:
   - Clone or download this repository to your local machine.
   - Open the `JavaHttpServer` class in your preferred Java development environment.

3. **Configuration**:
   - Update the `WEB_ROOT` and `OTHER_ROOT` variables in the `JavaHttpServer` class to specify the paths to your htdocs and other_docs directories. Make sure to replace these paths with the actual paths to your web content.

4. **Run the Server**:
   - Build and run the `JavaHttpServer` class in your Java development environment. The server will start listening on port 2728.

## Usage

### Serving HTML and PHP Files

1. Place your HTML and PHP files inside the `htdocs/other_docs` directory.
   - By default: [http://localhost:2728](http://localhost:2728) serves you the index.php file inside htdocs directory.

2. Access your files through a web browser using the following format:
   - For HTML files: [http://localhost:2728/your_html_file.html](http://localhost:2728/your_html_file.html)
   - For PHP files: [http://localhost:2728/your_php_file.php](http://localhost:2728/your_php_file.php)

### Handling POST Requests

- To make a POST request, use the [http://localhost:2728/index.php](http://localhost:2728/index.php) URL in your web browser. This will execute the `index.php` file with a POST request.

### Server Logs

- The server will log incoming connections and requests to the console if the `verbose` variable is set to `true` in the `JavaHttpServer` class.

## Features

- Supports GET and POST requests.
- Executes PHP files with POST data.
- Serves HTML and PHP files.
- Customizable web content directories.

## Contributing

- If you find issues or want to improve this project, please feel free to contribute by opening issues or submitting pull requests on the [GitHub repository](https://github.com/your/repository).

## License

- This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



