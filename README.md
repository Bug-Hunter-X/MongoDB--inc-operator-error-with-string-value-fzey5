# MongoDB $inc operator error with string value

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment or decrement a numerical value by a specified amount.  However, attempting to increment a field that is not a number or contains a string value will result in an error.

The `bug.js` file shows the incorrect usage, while `bugSolution.js` provides the corrected code.

## Bug
Attempting to increment a field with a string value leads to an error because the `$inc` operator expects a numerical value. 