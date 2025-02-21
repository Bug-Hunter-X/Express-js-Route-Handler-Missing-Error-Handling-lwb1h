# Express.js Route Handler Missing Error Handling

This repository demonstrates a common error in Express.js route handlers: missing error handling for invalid input.  Specifically, the `/users/:id` route does not handle cases where `req.params.id` is not a valid number, leading to unexpected errors.

The `bug.js` file shows the erroneous code. The `bugSolution.js` file provides a corrected version that includes robust error handling.