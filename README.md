# Calculator

A simple command-line calculator. Choose addition, subtraction, division or multiplication from a menu, enter two numbers and it gives you the answer.

This was the first app I completed in Python (September 2022). It was my first time writing my own functions and building a menu the user can choose from.

## Features

- Menu with four operations: addition, subtraction, division and multiplication
- Each operation has its own function
- Asks again if the menu choice isn't valid

## Built with

- Python 3

## Running it

You need Python 3. No extra packages are required.

```
python3 CalCul.py
```

## Example

```
Please select from the following:

[1]  Addition

[2]  Subtraction

[3]  Division

[4]  Multiplication

> 1
Please enter your first number: 12
Please enter your second number: 30
Your answers added together are: 42

Good Bye
```

## What I learned

- Writing functions that take arguments and return a value
- Converting user input from text to numbers
- Using `if` statements and a loop to handle a menu choice

## Ideas for improvement

- Accept decimal numbers, not just whole numbers
- Handle division by zero and input that isn't a number
- Let the user do more than one calculation before quitting