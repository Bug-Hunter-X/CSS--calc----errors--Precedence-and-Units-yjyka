# CSS `calc()` Gotchas: Operator Precedence and Units

This repository demonstrates a common issue with the CSS `calc()` function: unexpected results caused by incorrect operator precedence or inconsistent units.

The `bug.css` file shows the problematic code. The `bugSolution.css` file provides the corrected version.

## Problem

Incorrect unit usage or operator precedence can lead to unexpected results and render errors.

## Solution

Always ensure consistent units within `calc()` expressions.  Explicitly specify units for all values (e.g., `10px` instead of `10`). Be mindful of operator precedence and use parentheses to group expressions correctly.