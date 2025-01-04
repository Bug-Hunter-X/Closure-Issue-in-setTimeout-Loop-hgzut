# JavaScript Closure Issue in setTimeout Loop

This repository demonstrates a common closure issue encountered when using `setTimeout` within a loop in JavaScript.

The `bug.js` file contains code that exhibits this issue.  The expected output would be numbers 0-9, each printed after a 1-second delay. However, due to the closure's behavior, the output will be 10 ten times. 

The solution to this problem is shown in `bugSolution.js`.