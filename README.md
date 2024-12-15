# MongoDB $inc Operator Error
This example demonstrates an incorrect use of the `$inc` operator in MongoDB. The `$inc` operator is used to increment a numerical value by a specified amount.  However, providing a string value instead of a number will lead to an error.  The solution shows the correct way to use the `$inc` operator.

## Bug
The bug arises from passing a string ('1') to the $inc operator instead of a number (1). This is because the increment operation requires a numeric value.