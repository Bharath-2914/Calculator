# Calculator
Here is a sample README file for your calculator project:

---

# Java Swing Calculator

A simple calculator built using Java Swing that supports basic arithmetic operations, square root, power operations, and maintains a calculation history. The calculator also includes keyboard support for input.

## Features

- **Basic Arithmetic**: Addition, subtraction, multiplication, and division.
- **Square Root**: Calculates the square root of a number.
- **Power Operation**: Supports raising a number to a power.
- **Decimal Points**: Allows for decimal inputs.
- **Delete and Clear**: Options to delete the last digit or clear the entire input.
- **History**: Maintains a history of calculations, viewable on request.
- **Keyboard Support**: Supports keyboard input for numbers and basic operators.

## Screenshot
![Calculator Screenshot](path_to_screenshot_image)

## Prerequisites

- Java Development Kit (JDK) installed.
- IntelliJ IDEA or any Java-compatible IDE.

## Installation and Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/Java-Swing-Calculator.git
   cd Java-Swing-Calculator
   ```

2. **Open in IntelliJ IDEA**
   - Open the project in IntelliJ IDEA or your preferred IDE.
   - Compile and run the `Calculator` class.

## Usage

- Run the `Calculator` application.
- Click buttons or use your keyboard to enter numbers and perform operations.
- Use the following functionalities:
  - **C**: Clears the entire display.
  - **Del**: Deletes the last character in the display.
  - **√**: Calculates the square root of the current number.
  - **^**: Sets the current number to be raised to the power of the next number.
  - **History**: Displays a list of past calculations.

## Code Structure

- **Calculator**: The main JFrame class that sets up the UI components and handles all button actions.
- **Event Handling**: Each button’s `ActionListener` processes user inputs and displays results.
- **Keyboard Support**: Basic keyboard functionality is supported for numeric inputs and operations.

## Example Code Snippet

```java
if (e.getSource() == addButton) {
    num1 = Double.parseDouble(display.getText());
    operator = '+';
    display.setText("");
}
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Java Swing Documentation](https://docs.oracle.com/javase/tutorial/uiswing/)
- Stack Overflow and other Java communities for their helpful resources.
