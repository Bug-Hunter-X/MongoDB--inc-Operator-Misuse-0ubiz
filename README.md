# MongoDB $inc Operator Bug

This example demonstrates an issue with the MongoDB `$inc` operator. Incorrect use of `$inc` can lead to unexpected behavior and data inconsistencies. The provided `bug.js` file shows the incorrect usage and the `bugSolution.js` shows the correct implementation.

**Problem:** The initial code attempts to increment fields 'a' and 'b' but might fail or have unintended effects if the document doesn't exist or has a different structure. 