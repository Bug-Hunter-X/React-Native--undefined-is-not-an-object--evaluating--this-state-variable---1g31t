# React Native: undefined is not an object (evaluating 'this.state.variable')
This repository demonstrates a common React Native error: "undefined is not an object (evaluating 'this.state.variable')". This error arises when you attempt to access a state variable before it's been properly initialized.  The bug.js file showcases the problematic code, while bugSolution.js provides the corrected version.

**Problem:** Incorrectly accessing state before it's ready, often due to asynchronous operations or improper lifecycle management.

**Solution:** Ensure state variables are properly initialized and accessed only after they've been set.  This often involves using asynchronous techniques like async/await and placing state updates within appropriate lifecycle methods (componentDidMount for instance).