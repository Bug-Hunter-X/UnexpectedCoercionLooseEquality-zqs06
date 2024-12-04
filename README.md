# JavaScript Loose Equality Bug

This repository demonstrates a common JavaScript bug related to loose equality (`==`) and how to avoid it using strict equality (`===`). Loose equality can lead to unexpected type coercion, resulting in errors that are difficult to track down.  The example shows a function where the improper use of `==` for null checking may cause unexpected outcomes. Using strict equality eliminates this problem.

## How to Reproduce

1. Clone the repository.
2. Open `bug.js` and `bugSolution.js`. Compare the two implementations.
3. Run the tests (if any are added).

## Solution

Always use strict equality (`===`) when comparing values in JavaScript, especially when null checks are involved.