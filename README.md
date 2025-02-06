# Incorrect Null Handling in Addition Function

This repository demonstrates a common error in JavaScript: incorrect handling of `null` values.  The `foo` function attempts to add two numbers but fails to handle the case where either input is `null`.  The provided solution demonstrates a more robust approach, ensuring that `null` values are treated appropriately.

## Bug

The original `foo` function returns 0 if either `a` or `b` is `null`. This is incorrect if we want to treat `null` as 0.   A more sophisticated approach might throw an error, use a default value, or otherwise indicate an issue when `null` is encountered.

## Solution

The solution demonstrates how to handle `null` values more gracefully. The solution checks for null and converts it to zero before the summation.