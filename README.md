# Post-increment Operator in C
This example demonstrates a common confusion with the post-increment operator in C. The code intends to print the value of x, then increment it, but the order of operations might lead to unexpected results.

The `bug.c` file contains code with the post-increment issue, and `bugSolution.c` provides a corrected version.

## Problem:
The post-increment operator (`x++`) first returns the current value of `x` and then increments it. This means the first `printf` statement prints the original value (5), but the second `printf` statement prints the incremented value (6). This might be unexpected behavior for someone unfamiliar with this operator.