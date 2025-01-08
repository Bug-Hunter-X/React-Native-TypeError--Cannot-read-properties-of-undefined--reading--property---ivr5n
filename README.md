# React Native TypeError: Cannot read properties of undefined (reading 'property')

This repository demonstrates a common error in React Native applications: `TypeError: Cannot read properties of undefined (reading 'property')`.  The error arises when attempting to access a property of an object that is currently null or undefined.  This often happens when dealing with asynchronous data fetching or component lifecycles.

The `bug.js` file contains the problematic code, while `bugSolution.js` offers a solution using optional chaining and nullish coalescing operators to handle the potential undefined values gracefully.

## How to Reproduce

1. Clone this repository.
2. Navigate to the project directory.
3. Run `npm install` to install dependencies.
4. Run `npx react-native run-android` or `npx react-native run-ios` to run the app.
5. Observe the error in the console.