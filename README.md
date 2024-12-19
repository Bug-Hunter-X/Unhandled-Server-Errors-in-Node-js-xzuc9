# Unhandled Server Errors in Node.js

This repository demonstrates a common error in Node.js server development: insufficient error handling. The provided `bug.js` file showcases a server that crashes without proper logging or graceful handling of errors.

The `bugSolution.js` file offers a solution with improved error handling, preventing unexpected crashes and providing more informative error messages.

## Bug Description
The server in `bug.js` doesn't handle potential errors during the server setup or request processing. If an error occurs, the server crashes silently without any useful output.

## Solution
The `bugSolution.js` file demonstrates how to correctly handle errors using a `try...catch` block and logging errors to the console.  This solution prevents server crashes and makes debugging significantly easier.