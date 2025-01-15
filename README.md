# JavaScript Loose Equality and Null Checks

This repository demonstrates a common JavaScript bug related to loose equality (==) when checking for null or undefined values.

The `bug.js` file contains code that uses loose equality, which can lead to unexpected behavior. The `bugSolution.js` file shows the corrected version using strict equality (===).

**Problem:** Loose equality (==) performs type coercion, which can result in unexpected true or false values when comparing with null or undefined.

**Solution:**  Using strict equality (===) avoids type coercion and provides more reliable null checks. 

This example highlights the importance of using strict equality in JavaScript for better code clarity and reliability.