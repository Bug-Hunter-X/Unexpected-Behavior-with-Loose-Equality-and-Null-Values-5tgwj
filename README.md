# JavaScript Loose Equality Bug

This repository demonstrates a common JavaScript bug related to loose equality (`==`) and handling `null` values.  The `bug.js` file contains code exhibiting the problem, while `bugSolution.js` offers a corrected version.

## Bug Description

The original code uses loose equality to check for `null` inputs.  This can lead to unexpected behavior due to JavaScript's type coercion rules.  The corrected code uses strict equality (`===`) to prevent unintended type conversions.

## How to Run

1. Clone this repository.
2. Open `bug.js` and `bugSolution.js` in a JavaScript environment (e.g., browser console, Node.js).
3. Run the code to observe the different behaviors.