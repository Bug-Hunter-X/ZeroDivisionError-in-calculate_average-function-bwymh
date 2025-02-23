# Python code with a ZeroDivisionError

This repository contains a Python function `calculate_average` that calculates the average of a list of numbers.  However, the function has a bug: it does not correctly handle cases where the input list is empty or contains only zeros. This leads to a `ZeroDivisionError` when attempting to divide by zero.  The `bugSolution.py` file provides a corrected version of the function that addresses this issue.

**To reproduce the error:**

1. Run `bug.py`.
2. Observe the `ZeroDivisionError` when the function is called with an empty list or a list with only zeros.

**Solution:**

The solution is provided in `bugSolution.py`. The improved function includes a check for an empty list, handling this by returning 0.  Additionally, a check for the sum being zero ensures that a division by zero is avoided in such cases.