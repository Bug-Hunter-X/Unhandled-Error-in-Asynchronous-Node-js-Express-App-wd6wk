# Unhandled Error in Asynchronous Node.js Express App

This repository demonstrates a common error in Node.js applications involving unhandled exceptions within asynchronous callbacks.  The `bug.js` file showcases the problem, while `bugSolution.js` provides a corrected version with proper error handling.

## Problem

The original code simulates an asynchronous operation (using `setTimeout`) that might throw an error.  If the error occurs, it's not caught, resulting in the server crashing.

## Solution

The solution implements proper error handling using `try...catch` blocks within the asynchronous callback.  This ensures that errors are caught gracefully and the server remains responsive.