# Simple Calculator Project

This project implements a simple calculator using HTML and JavaScript. Users can input two values, choose a mathematical operation from a dropdown menu, and click the "Calculate" button to obtain the result. The code is structured to handle basic arithmetic operations such as addition, subtraction, multiplication, and division.

## Usage

1. Open the `index.html` file in a web browser.
2. Enter numerical values in the "Enter value 1" and "Enter value 2" input fields.
3. Choose a mathematical operation from the dropdown menu.
4. Click the "Calculate" button to perform the selected operation.
5. The result will be displayed in the "Result" input field.

## Code Structure

- `index.html`: Contains the HTML structure for the calculator interface, input fields, dropdown menu, and result display.
- `script.js`: Implements the JavaScript logic for performing calculations based on user input.

## How it Works

1. The `calculate()` function is triggered by clicking the "Calculate" button.
2. It retrieves the values of the two input fields (`value1` and `value2`) and the selected operation (`math`) from the dropdown menu.
3. A `switch` statement performs the corresponding arithmetic operation.
4. The result is displayed in the designated input field (`result`).

## Mathematical Operations

- **Addition:** `+`
- **Subtraction:** `−`
- **Multiplication:** `×`
- **Division:** `÷`

## Important Notes

- The code assumes valid numerical inputs from the user.
- Division by zero is not handled.
- The result is displayed directly in the input field without formatting or validation.

Feel free to explore and use this simple calculator for basic arithmetic calculations!
