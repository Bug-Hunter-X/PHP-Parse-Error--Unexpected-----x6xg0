# PHP Parse Error: Unexpected '('

This repository demonstrates a common PHP parse error caused by incorrectly calling a function without parentheses.  The `bug.php` file contains the erroneous code, while `bugSolution.php` provides the corrected version.

## Bug

The issue arises from attempting to call a function without the required parentheses. PHP interprets this as an attempt to access a property or constant instead of executing the function.

## Solution

The solution involves simply adding parentheses to properly call the function. Ensure all function calls are correctly parenthesized to avoid this common parsing error.