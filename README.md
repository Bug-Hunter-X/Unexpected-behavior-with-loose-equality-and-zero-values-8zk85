# Unexpected Behavior with Loose Equality and Zero Values in JavaScript

This repository demonstrates a common JavaScript error involving loose equality (==) and zero values.  The function `foo` is intended to divide two numbers, returning 0 if either input is 0. However, due to the behavior of loose equality, unexpected results occur.

The `bug.js` file showcases the erroneous behavior. The `bugSolution.js` file demonstrates the corrected implementation using strict equality (===).