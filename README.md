# Off-by-one Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over arrays.  The error occurs when the loop condition incorrectly includes the last index beyond the array bounds, leading to an `ArrayIndexOutOfBoundsException`. The solution shows the correct way to iterate through an array using the `<` operator instead of `<=`.

## Bug
The `Bug.java` file contains the buggy code. The `for` loop's condition `i <= arr.length` attempts to access an index that is out of bounds.

## Solution
The `BugSolution.java` file provides the corrected code. The `for` loop's condition is changed to `i < arr.length` to avoid the error.
