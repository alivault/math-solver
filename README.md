# Math Solver

This project is a simple, yet powerful Math Solver that runs in the web browser. It is primarily written in JavaScript, HTML, and CSS, offering a straightforward and user-friendly interface to input mathematical equations and receive their calculated results. 

The JavaScript part of the project is responsible for parsing and calculating the entered mathematical equations. The script accepts operations including addition, subtraction, multiplication, division, and exponentiation. It uses recursive functions to adhere to the correct order of operations (parentheses, exponents, multiplication and division, addition and subtraction - often referred to by the acronym PEMDAS).

The HTML part lays out the structure of the web page, including a form for entering the equations and a section for displaying the results. 

## How to Use

1. Go to https://www.aliabbas.dev/math-solver/
2. In the input field provided, enter your mathematical equation using standard mathematical notation. The equation can include the following operators: 
    * Addition: `+`
    * Subtraction: `-`
    * Multiplication: `*`
    * Division: `/`
    * Exponentiation: `^`
3. Press the "Solve" button to calculate the result. The result of the operation will be displayed in the 'results' section below the input field.

## Project Limitations

While the project aims to handle a variety of mathematical equations accurately, it's important to note a few limitations:

* The solver assumes well-formatted input and doesn't have comprehensive error handling. It might not function correctly if the user input isn't a valid mathematical expression.
* The code might have issues with edge cases involving scientific notation due to its method for identifying the addition and subtraction operations.
