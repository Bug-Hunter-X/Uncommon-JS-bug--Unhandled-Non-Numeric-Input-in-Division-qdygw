# Uncommon JS Bug: Unhandled Non-Numeric Input in Division

This repository demonstrates a subtle bug in a simple arithmetic function and presents a solution.

## Bug Description

The `divide` function in `bug.js` correctly handles division by zero. However, it does not explicitly check if inputs `a` and `b` are numeric values. If either is not a number (e.g., a string), the code will throw a `TypeError` instead of a more informative error message.

## Solution

The `bugSolution.js` file addresses this issue by adding input validation to ensure that both `a` and `b` are numbers before performing the division.

## How to run

1. Clone the repository.
2. Run the files using a JavaScript runtime environment (e.g., Node.js).

## Lessons Learned

- Always validate user inputs, especially in mathematical functions.
- Handle different types of errors appropriately to provide better debugging information.
- Comprehensive error handling enhances code reliability and robustness.