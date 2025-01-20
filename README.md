# Unhandled Exception in Asynchronous Express.js Route Handler

This repository demonstrates a common error in Node.js applications using Express.js: unhandled exceptions within asynchronous route handlers.

The `bug.js` file contains code that simulates an asynchronous operation.  If a random number is less than 0.5, it returns a successful response. Otherwise, it throws an error without proper error handling, causing the server to crash.

The `bugSolution.js` file provides a corrected version with proper error handling using `try...catch` blocks, ensuring graceful handling of potential errors and preventing server crashes.