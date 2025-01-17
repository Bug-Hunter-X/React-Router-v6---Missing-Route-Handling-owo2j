# React Router v6 - Missing Route Handling

This repository demonstrates a common error in React Router v6:  improper handling of routes that don't exist, leading to unexpected behavior or crashes. The `bug.js` file showcases the issue, while `bugSolution.js` provides a corrected version.

## Problem

In the initial implementation, a route for `/users` is defined in the application, but is never used in the routing configuration in `App.js`. When a user attempts to navigate to `/users`,  React Router will throw an error, or potentially display nothing.