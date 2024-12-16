# Subtle Null Handling Bug in JavaScript Function

This repository demonstrates a subtle bug in a simple JavaScript function that handles null values. The function `foo` adds two numbers but returns `null` if either input is `null`.  This behavior might not be desired in all cases.  The `bug.js` file contains the buggy code, and `bugSolution.js` provides a more robust solution.

## Bug Description
The function incorrectly treats `null` values as stopping points, returning `null` immediately if either input is `null`.  A more flexible approach might involve defaulting `null` values to 0, throwing an error, or implementing other null-handling strategies.