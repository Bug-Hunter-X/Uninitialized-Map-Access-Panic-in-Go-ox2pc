# Uninitialized Map Access in Go

This repository demonstrates a common error in Go: attempting to access a map before it's initialized.  This will cause a runtime panic.  The solution shows how to safely initialize and access a map.

## Bug
The `bug.go` file contains code that attempts to assign a value to a map that hasn't been initialized, leading to a panic.

## Solution
The `bugSolution.go` file provides a corrected version, initializing the map before accessing it, preventing the panic.