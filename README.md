# JavaScript Null Handling in Functions

This repository demonstrates a common error in JavaScript: forgetting to explicitly check for null or undefined values as function inputs.

The `bug.js` file shows a simple addition function that is vulnerable to errors if null values are passed. The `bugSolution.js` demonstrates the corrected function which uses appropriate null checks to avoid these errors.

## How to run

1. Clone this repository.
2. Open the `bug.js` and `bugSolution.js` files in your favorite code editor.
3. Run the `bug.js` to see the error behavior.
4. Observe that the `bugSolution.js` handles null values gracefully.

This example highlights the importance of defensive programming and how simple null checks can prevent significant problems in your applications.