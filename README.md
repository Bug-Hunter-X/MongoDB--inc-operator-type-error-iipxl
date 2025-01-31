# MongoDB $inc operator type error
This example demonstrates an incorrect usage of the `$inc` operator in MongoDB's `updateOne` method. The `$inc` operator is used to increment a numerical field by a given value. However, in this case, a string is provided as the value, which leads to an error.

## Bug
The original code attempts to increment the `field` by the value "value", which is not a valid number. This results in an error.

## Solution
The corrected code provides a numerical value to the `$inc` operator. This ensures that the increment operation works as expected.
