# CSS `calc()` Function Errors

This repository demonstrates an uncommon error related to the CSS `calc()` function, specifically concerning negative width calculations and whitespace issues.  The `bug.css` file contains the problematic code, while `bugSolution.css` offers a solution.

The primary problem arises when using percentages and viewport units (vw) together in `calc()` where the subtraction might result in a negative width. Browsers handle negative widths inconsistently, often resulting in unexpected rendering or even parsing errors.

Additionally, improper spacing within the `calc()` function can cause parsing issues.

The solution provided addresses both of these problems by implementing a more robust calculation method. 