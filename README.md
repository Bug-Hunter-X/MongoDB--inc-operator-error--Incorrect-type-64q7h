# MongoDB $inc Operator Error: Incorrect Type

This example demonstrates a common error when using the `$inc` operator in MongoDB update queries.  The `$inc` operator is designed to increment a numerical field by a specified value, but it's crucial to ensure that the value provided is a number, not a string.

The provided `bug.js` demonstrates the incorrect use of the `$inc` operator, where a string ('1') is used instead of a number (1).  The corrected version (`bugSolution.js`) shows the proper usage.