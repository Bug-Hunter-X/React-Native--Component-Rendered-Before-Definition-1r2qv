# React Native: Component Rendered Before Definition

This repository demonstrates a common error in React Native where a component is rendered before it has been fully defined, leading to a runtime error.  The solution involves careful consideration of import order and potentially using lazy loading techniques.

## Bug
The `bug.js` file contains the incorrect code that causes the error. The solution can be found in `bugSolution.js`.

## Solution
The solution addresses the issue by ensuring that all components are defined and available before rendering.

## How to reproduce the bug
1. Clone the repository.
2. Run `npm install`.
3. Run the app.
4. Observe the error message in the console.

## How to fix the bug
Follow the updated import order in `bugSolution.js` or explore lazy loading methods for more complex scenarios.