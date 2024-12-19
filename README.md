# RecursionError in Python: Exceeding Maximum Recursion Depth

This repository demonstrates a common error in Python involving recursive functions and how to mitigate it.

The `bug.py` file contains a recursive function that calculates Fibonacci numbers.  When called with a sufficiently large input (e.g., 35), it exceeds the maximum recursion depth, causing a `RecursionError`.

The `bugSolution.py` file shows a solution using memoization to prevent excessive recursion and efficiently calculate Fibonacci numbers.