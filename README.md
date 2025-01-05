# Unexpected Font Size Inheritance in CSS

This repository demonstrates an uncommon issue related to CSS specificity and inheritance.  The problem involves a link (`<a>`) element nested within a paragraph (`<p>`) element which inherits unexpected font sizes from its parent elements and the parent container.

## Problem

The provided CSS exhibits an unexpected font size inheritance behavior.  The link's font size is not what is expected due to the inheritance chain in conjunction with specificity considerations.

## Solution

The solution addresses the unexpected inheritance and provides a clear and consistent font size for the link, ensuring predictable styling across elements.  The fix is explained in detail in the comments within `bugSolution.css`.

This example highlights the subtle nuances of CSS specificity, highlighting areas of potential confusion for developers.