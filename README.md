# Unexpected Addition Behavior with undefined and null

This repository demonstrates an unusual behavior in JavaScript concerning the addition operator (+) when used with `undefined` and `null` values.

In JavaScript's loose typing system, adding `undefined` to a number results in `NaN` (Not a Number), while adding `null` to a number treats `null` as 0.

The `bug.js` file shows this unexpected behavior. The `bugSolution.js` file provides a solution on how to handle these cases.

This is a common gotcha for developers new to JavaScript, highlighting the need for careful type handling and input validation.