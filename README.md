# Postfix Expression Evaluator

This C program evaluates a postfix expression using a stack data structure. It processes the expression, applies the operators, and returns the result. The program supports the four basic arithmetic operations: addition, subtraction, multiplication, and division.

## Features

- Evaluates postfix expressions.
- Supports the four basic operators: `+`, `-`, `*`, and `/`.
- Handles division by zero errors.
- Uses a stack for storing operands and performing operations.

## Files

- `postfix_evaluator.c`: Contains the C code for evaluating postfix expressions.

## Functions

### `Stack* createStack()`
- Creates a new empty stack.
  
### `void push(Stack* stack, float data)`
- Pushes a float operand onto the stack.

### `float pop(Stack* stack)`
- Pops a float operand from the stack.
- Returns `-1.0` if the stack is empty.

### `int isOperator(char c)`
- Checks if the character is a valid operator (`+`, `-`, `*`, `/`).

### `float evaluatePostfix(char* postfix)`
- Evaluates the given postfix expression using a stack.
- Returns the result of the evaluation.

### `int main()`
- Main function that reads a postfix expression from the user and displays the result.

