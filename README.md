# JavaScript Type Coercion Bug

This repository demonstrates a common JavaScript bug caused by loose typing and automatic type coercion in arithmetic operations.  The `foo` function is intended to add two numbers, but due to JavaScript's dynamic typing, it concatenates strings when a string is provided as an argument.  The `bugSolution.js` provides a corrected version that handles type checking and conversion explicitly.

## How to reproduce

1. Clone the repository
2. Run `bug.js` using Node.js or a similar JavaScript runtime environment.