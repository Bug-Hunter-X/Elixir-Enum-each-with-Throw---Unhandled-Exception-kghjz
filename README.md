# Elixir Enum.each with Throw - Unhandled Exception

This example demonstrates a common error in Elixir when using `Enum.each` with `throw`.  If an exception is thrown within the `Enum.each` anonymous function, the program will terminate abruptly unless proper exception handling is implemented.

The `bug.ex` file contains the problematic code.  The `bugSolution.ex` file shows the corrected version.