# Binary Calculator - Lab Project

## Overview
This project is a binary calculator developed as part of a lab for my school. It allows users to perform basic arithmetic and bitwise operations on binary numbers using a web-based interface. The project is built using Java and Spring Boot for backend logic and JUnit for testing.

## Features
- Addition, multiplication, AND, and OR operations on binary numbers.
- Input validation to ensure only binary numbers are accepted.
- Web-based UI for user interaction.
- JSON API endpoints for performing operations programmatically.
- Comprehensive test coverage using JUnit and MockMvc.

## Technology Used
- **Java**: Core programming language.
- **Spring Boot**: Framework for building the web application.
- **Thymeleaf**: Template engine for rendering the web UI.
- **JUnit**: Testing framework for unit and integration testing.
- **MockMvc**: Used for testing the API endpoints.

## Setup & Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/binary-calculator.git
   ```
2. Navigate to the project directory:
   ```sh
   cd binary-calculator
   ```
3. Build the project using Maven:
   ```sh
   mvn clean install
   ```
4. Run the application:
   ```sh
   mvn spring-boot:run
   ```
5. Access the web UI at `http://localhost:8080`

## Usage
- Enter two binary numbers in the input fields.
- Choose an operation (`+`, `*`, `|`, `&`).
- Click submit to view the result.
- The application will validate the input and display an error message if invalid numbers are entered.

## API Endpoints
- **Addition:** `GET /add_json?operand1=101&operand2=11`
- **Multiplication:** `GET /multiply_json?operand1=101&operand2=11`
- **Bitwise AND:** `GET /and_json?operand1=101&operand2=11`
- **Bitwise OR:** `GET /or_json?operand1=101&operand2=11`

## Testing
Run unit tests using:
```sh
mvn test
```
This will execute JUnit tests to ensure all functionalities work correctly.

## Contributions
This project was developed as part of a school lab assignment, so external contributions are not required.

## License
This project is for educational purposes and does not have an official license.

