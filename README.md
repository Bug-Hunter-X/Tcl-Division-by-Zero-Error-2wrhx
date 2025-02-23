# Tcl Division by Zero Bug

This repository demonstrates a common error in Tcl programming: division by zero. The `bug.tcl` file contains a procedure that does not handle this case correctly, while `bugSolution.tcl` provides a corrected version.

The bug is easily triggered by calling the procedure with 0 as the first argument, resulting in a runtime error.

The solution implements input validation to prevent the error and gracefully handles the case of division by zero.