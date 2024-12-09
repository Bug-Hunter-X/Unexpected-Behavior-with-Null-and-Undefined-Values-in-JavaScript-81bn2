# JavaScript Null and Undefined Handling

This repository demonstrates a common JavaScript error related to unexpected behavior when dealing with `null` and `undefined` values using loose comparison. The `bug.js` file shows the erroneous code, while `bugSolution.js` provides a corrected implementation.

## Problem

JavaScript's loose comparison (`==`) can lead to unexpected results, particularly when comparing `null` and `undefined` values.  This often leads to silent errors that are hard to debug.

## Solution

The recommended approach is to use strict equality (`===`) which avoids type coercion and provides more reliable comparisons.  This ensures that you are comparing the exact values and types.

## How to run

1. Clone the repository
2. Open the `bug.js` and `bugSolution.js` files in your preferred JavaScript environment or browser's console.
3. Observe the difference in output between the original and corrected code.