# Unexpected Null/Undefined Behavior in JavaScript

This repository demonstrates a common error in JavaScript related to loose equality (`==`) when dealing with `null` and `undefined` values.  The `bug.js` file showcases the problem, while `bugSolution.js` provides the corrected code.

## Problem

JavaScript's loose equality can lead to unexpected comparisons between `null` and `undefined`, resulting in incorrect program logic.  This example illustrates the issue and how to resolve it using strict equality (`===`).

## Solution

The solution employs strict equality (`===`) to ensure precise comparisons, eliminating the ambiguity introduced by loose equality.

## How to run

1. Clone the repository.
2. Navigate to the project directory.
3. Run the code using Node.js: `node bug.js` and `node bugSolution.js`.