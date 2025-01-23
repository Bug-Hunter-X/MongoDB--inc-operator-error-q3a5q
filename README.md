# MongoDB $inc Operator Error

This repository demonstrates an example of an incorrect usage of the MongoDB `$inc` operator and how to fix it. The `$inc` operator is used to increment a numerical field by a specified value.  However, providing a string value will lead to an error or unexpected results.

## Bug
The provided JavaScript code attempts to increment the age field by '1' (a string), which is incorrect. The correct usage should pass an integer value.

## Solution
The solution involves changing the increment value from a string ('1') to a number (1).