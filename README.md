# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java that can lead to an `ArrayIndexOutOfBoundsException`.  The error occurs when iterating over an array and the loop condition is not properly handled. 

## Bug Description

The provided Java code attempts to populate an integer array. The loop iterates one element beyond the array's bounds, causing an index out of bounds exception.

## Solution

The solution corrects the loop condition to ensure it iterates within the valid index range of the array.
