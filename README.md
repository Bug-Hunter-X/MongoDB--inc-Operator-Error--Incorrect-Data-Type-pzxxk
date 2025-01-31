# MongoDB $inc Operator Error
This repository demonstrates a common error when using the `$inc` operator in MongoDB. The error occurs when a string is used instead of a number to increment a field. 

## Bug Description
The provided code attempts to increment the `counter` field by 1. However, it uses the string "1" instead of the number 1. This results in an error because the `$inc` operator requires a numerical value.

## Solution
The solution involves correcting the data type used to increment the `counter` field by replacing the string "1" with the number 1.