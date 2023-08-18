# Calculator App with tkinter

This is a simple calculator application built using the tkinter library in Python. The calculator provides basic arithmetic operations and includes features like square root, percentage calculation, and more.

## Features

- Addition, subtraction, multiplication, and division.
- Square root and percentage calculation.
- Clear Entry (CE), Clear All (C), and Backspace (⌫) functions.
- Sign inversion and decimal point support.
- Interactive visual feedback for buttons.

## Requirements

- Python 3.x
- `tkinter` library (included in standard library)
- `math` library (included in standard library)

## How to Use

1. Open a Jupyter Notebook.
2. Copy and paste the code from the `calculator_app.py` file into a code cell.
3. Run the code cell to initialize the calculator.

4. The calculator GUI window will appear. Use the buttons to perform calculations and interact with the calculator.

## Button Functionality

- **Numbers and Operators**: Clicking on numeric and operator buttons appends them to the current expression.
- **=**: Evaluates the current expression and displays the result.
- **1/x**: Calculates the reciprocal of the current number.
- **x^2**: Calculates the square of the current number.
- **√**: Calculates the square root of the current number.
- **+/-**: Toggles the sign of the current number.
- **%**: Calculates the percentage of the current number.
- **CE**: Clears the current entry to "0".
- **C**: Clears the entire expression to "0".
- **⌫**: Removes the last character from the current entry.

## Visual Feedback

- Buttons change color when the cursor hovers over them.
- The "=" button changes color in response to hovering.
- Active and normal colors are used for better interactivity.

## Error Handling

- The calculator handles exceptions and displays "Error" in case of invalid inputs or calculations.

## License

This project is licensed under the MIT License. Feel free to use and modify it according to your needs.

---

Feel free to contribute or provide suggestions to improve this calculator application. If you encounter any issues, please report them in the Issues section of this repository.
