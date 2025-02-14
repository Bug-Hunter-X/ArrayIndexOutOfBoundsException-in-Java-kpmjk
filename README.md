# Java ArrayIndexOutOfBoundsException Bug
This repository contains a simple Java program that demonstrates an ArrayIndexOutOfBoundsException. The bug is caused by an incorrect loop condition in the code, leading to an attempt to access an index beyond the array's boundaries.

## Bug Description
The Java program creates an integer array of size 5. It then iterates through the array using a `for` loop, assigning values to each element. However, the loop condition `i <= arr.length` is incorrect.  It should be `i < arr.length` to avoid the `ArrayIndexOutOfBoundsException`.  The provided solution corrects this loop condition, preventing the error.

## Solution
The solution file provides the corrected code with the `i < arr.length` condition in the `for` loop, fixing the bug and preventing the exception. 