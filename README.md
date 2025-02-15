# Java ArrayIndexOutOfBoundsException Bug

This repository demonstrates a common Java bug: an `ArrayIndexOutOfBoundsException`. The bug is caused by an off-by-one error in the loop accessing the array.

## Bug Description

The `BuggyArray.java` file contains a program that attempts to access an array element beyond its valid index, leading to an `ArrayIndexOutOfBoundsException`. The loop iterates one time too many.

## Solution

The `FixedArray.java` file provides a corrected version of the code. The loop condition is changed from `i <= arr.length` to `i < arr.length` to prevent the out-of-bounds access.