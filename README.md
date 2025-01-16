# Uncommon HTML Bug: Object assignment to innerHTML

This repository demonstrates an uncommon bug in HTML related to the incorrect usage of `innerHTML` with JavaScript objects.  The code attempts to assign a JavaScript object directly to `innerHTML`, which results in an unexpected outcome.  The solution demonstrates the correct approach.

## Bug
The bug involves attempting to assign a JavaScript object directly to the `innerHTML` property of an HTML element.  Browsers treat this differently than assigning a string, often resulting in an empty or unexpected result instead of rendering the object's contents.

## Solution
The correct approach is to convert the object into a string representation before assigning it to `innerHTML`.  This can be achieved using `JSON.stringify()`.

## How to run
1. Clone this repository.
2. Open `bug.html` in your browser to see the buggy behavior.
3. Open `bugSolution.html` to see the corrected code.