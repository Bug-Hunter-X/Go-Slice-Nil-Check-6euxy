# Go Slice Nil Check

This repository demonstrates a common error in Go involving nil slices and provides a solution.

## Bug

The `bug.go` file contains a function `myFunc` that iterates over a slice of integers.  However, it lacks a check to handle the case where the input slice is nil.  This can lead to a runtime panic if the function is called with a nil slice.

## Solution

The `bugSolution.go` file provides a corrected version of `myFunc`.  It first checks if the slice is nil before iterating, preventing the panic.
