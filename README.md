# CSS Specificity Gotcha: Unexpected Inheritance and Specificity Conflicts

This repository demonstrates a subtle bug related to CSS specificity and inheritance. The bug arises from unexpected behavior when combining class selectors and element selectors within nested elements.  Understanding how specificity is calculated in CSS is crucial for avoiding this type of error.

## The Bug

The `bug.css` file contains CSS code that produces an unexpected visual result due to the interaction of specificity and inheritance. The root cause is the conflict between different selectors targeting the same nested element.