# CSS Specificity Bug with !important

This repository demonstrates a subtle bug related to CSS specificity and the `!important` declaration.  The bug highlights a scenario where `!important` unexpectedly overrides a more specific selector.  The solution shows how to refactor the CSS to achieve the intended styling behavior without relying on `!important`.

## Bug Description
The bug occurs when a more specific CSS selector is overridden by a less specific selector that uses the `!important` declaration. This is counterintuitive to the typical specificity behavior of CSS.

## How to reproduce
1. Clone this repository.
2. Open `bug.css` and `bugSolution.css` to view the buggy and corrected CSS code respectively. 
3. Examine the unexpected styling behavior of the `.child` class in the `bug.css` and then compare it with the corrected styling behavior of the `.child` class in `bugSolution.css`. 

## Solution
The solution demonstrates how to rewrite the CSS to achieve the desired effect without using `!important`.   This approach follows best practices for CSS by resolving specificity conflicts in a cleaner, more maintainable way.
