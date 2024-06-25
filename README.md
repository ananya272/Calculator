# Calculator
Creating a calculator using HTML, CSS, and JavaScript involves designing the calculator interface with HTML, styling it with CSS, and then using JavaScript to handle the calculation logic. 
HTML: 
We create a div with the class calculator containing an input field to display the current value and a series of buttons representing the calculator keys. Each button has a value attribute that we use to identify the button in the JavaScript code.

CSS:
We style the calculator to center it on the page and give it a modern look.
The .calculator-screen class styles the display area of the calculator.
The .calculator-keys class sets up a grid layout for the calculator buttons.
Additional styles for the buttons to differentiate between number buttons, operator buttons, the equal sign, and the clear button.

JavaScript:
We define an object calculator to keep track of the current state of the calculator, including the display value, the first operand, the operator, and whether we are waiting for a second operand.
The updateDisplay function updates the calculator display to show the current value.
The handleKeyPress function processes button clicks and updates the state of the calculator accordingly.
The handleOperator function handles operator button clicks and performs calculations.
The calculate function performs the actual arithmetic operations.
The resetCalculator function resets the calculator to its initial state.
We add an event listener to the calculator keys to handle button clicks and call the appropriate functions.
This code will create a functional calculator that can perform basic arithmetic operations and update the display accordingly.
