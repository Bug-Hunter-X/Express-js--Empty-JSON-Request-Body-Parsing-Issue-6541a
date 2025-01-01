# Express.js Empty JSON Request Body Handling

This repository demonstrates a common issue and its solution when handling empty JSON request bodies in Express.js applications.

## Problem

When an empty JSON request body is sent to an Express.js server using `express.json()`, the `req.body` is undefined instead of an empty object. This can lead to unexpected behavior and errors in your application.

## Solution

The solution involves adding a check to handle empty request bodies gracefully.

## Setup

1. Clone the repository.
2. Run `npm install` to install the necessary dependencies.
3. Run `node bug.js` to start the server with the bug.
4. Run `node bugSolution.js` to start the server with the solution implemented.

## Contributing

Contributions are welcome!