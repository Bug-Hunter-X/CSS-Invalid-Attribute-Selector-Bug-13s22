# CSS Invalid Attribute Selector Bug

This repository demonstrates a common yet subtle bug in CSS: using an invalid attribute selector.  The bug results in styles not being applied because the attribute selector doesn't match any elements.

## Bug Description
The `bug.css` file contains CSS that attempts to style elements using an attribute selector that doesn't exist or doesn't match the element's attributes. This leads to unexpected styling behavior or lack thereof.

## Solution
The `bugSolution.css` file provides a corrected version of the CSS.  The fix involves verifying the existence of the attribute and value being used in the selector.  It may involve changing the attribute name or the value being checked for correct matching.

## How to reproduce
1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Observe the lack of expected styling on the affected elements.
4. Open `bugSolution.html` in a web browser.
5. Observe that the elements are now correctly styled.
