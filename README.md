# Go Nil Map Access Panic

This repository demonstrates a common error in Go: accessing a nil map.  Go maps are not automatically initialized; attempting to access a key in a nil map will result in a runtime panic.

## Bug

The `bug.go` file contains code that attempts to assign a value to a key in an uninitialized map.  This will lead to a panic.

## Solution

The `bugSolution.go` file provides a solution by checking if the map is nil before accessing it.  Alternatively, you can initialize the map before use.
