# CSS calc() Unexpected Behavior

This repository demonstrates a common issue encountered when using the `calc()` function in CSS: unexpected behavior when dealing with negative values or inconsistent units. 

The `bug.css` file contains code that reproduces the issue.  The `bugSolution.css` demonstrates how to correct the problem.  This issue arises because CSS properties like `width` and `height` cannot accept negative values. Using `calc()` to produce a negative value can lead to unexpected results, such as the element collapsing or rendering incorrectly. Inconsistent units also cause errors.

This is a relatively uncommon error, often missed by developers unfamiliar with the `calc()` function's limitations.