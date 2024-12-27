# Unexpected String Concatenation in JavaScript

This repository demonstrates a common JavaScript error caused by the language's loose typing system.  When adding a number and a string, JavaScript performs string concatenation instead of numerical addition, resulting in unexpected output.

## Bug
The `myFunction` adds two values, a number and a string.  Due to JavaScript's type coercion, the function concatenates the values as strings instead of performing numerical addition.

## Solution
The bug is solved by explicitly converting both inputs to numbers before addition using `parseInt()` or `Number()`. This ensures that the addition operation is performed numerically, resulting in the correct output.
