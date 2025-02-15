# Unexpected Type Coercion in Node.js

This repository demonstrates a common yet subtle error in JavaScript/Node.js: unexpected type coercion.  The `myFunction` example shows how passing a number and a string results in string concatenation instead of numerical addition.  The solution showcases techniques to avoid this issue.

## Bug
The `bug.js` file contains a function that incorrectly handles different data types, leading to unexpected results. 

## Solution
The `bugSolution.js` file provides a corrected version of the function, demonstrating how to handle type coercion explicitly and prevent unexpected behavior.