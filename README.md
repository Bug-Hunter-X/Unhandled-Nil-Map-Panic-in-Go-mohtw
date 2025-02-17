# Unhandled Nil Map Panic in Go

This repository demonstrates a common error in Go: panics caused by accessing a nil map.  Go maps are reference types; if not explicitly initialized, they are `nil`.  Attempting to read or write to a `nil` map results in a runtime panic, halting program execution.

The `bug.go` file showcases the problematic code. The `bugSolution.go` demonstrates how to prevent this panic using appropriate checks.