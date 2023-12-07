# Calculator Project Advent of Code

## Overview
This project is a simple web-based calculator designed to perform basic arithmetic operations. The calculator allows users to add, subtract, multiply, and divide numbers, as well as clear the display and delete the last entered digit. The project includes HTML, CSS, and JavaScript files to create the user interface and implement the calculator's functionality.

## Features
- Addition, subtraction, multiplication, and division operations.
- Clear button (C) to reset the calculator.
- Backspace button (&larr;) to delete the last entered digit.
- Responsive design for a better user experience on various devices.

## Files and Structure
- **index.html**: The main HTML file that defines the structure of the calculator interface.
- **style.css**: The CSS file containing styles for the calculator layout and appearance.
- **script.js**: The JavaScript file responsible for handling user input, performing calculations, and updating the display.

## How It Works
1. **HTML Structure**: The calculator layout is defined using HTML, with sections for the screen display and buttons arranged in rows.
2. **CSS Styling**: The CSS file styles the calculator, providing a clean and visually appealing interface.
3. **JavaScript Logic**:
   - Variables `runningTotal` and `buffer` are used to store the running total and the current input.
   - The `buttonClick` function is called when a calculator button is clicked, determining whether the input is a number or a symbol.
   - The `handleSymbol` function processes symbol inputs (e.g., C, &larr;, =, +, −, ×, ÷).
   - The `handleMath` function handles arithmetic operations and updates the running total.
   - The `flushOperation` function performs the actual calculation based on the previous operator.
   - The `handleNumber` function processes numeric inputs.
4. **Event Listeners**: Event listeners are set up to capture button clicks and trigger the appropriate actions.

## How to Use
1. Open the `index.html` file in a web browser.
2. Click on the calculator buttons to enter numbers and perform operations.
3. Use the C button to clear the calculator, the &larr; button to delete the last digit, and the = button to see the result of the calculation.

## Project Setup
No specific setup is required to run this project. Simply open the `index.html` file in a web browser, and the calculator will be ready for use.

## Future Enhancements
Possible future enhancements to consider:
- Adding support for decimal numbers.
- Implementing keyboard input for a more versatile user experience.
- Improving the visual design for a more polished appearance.

Feel free to fork and modify the code to suit your needs or contribute to the project's development. If you encounter any issues or have suggestions, please open an issue in the repository.

Enjoy calculating!