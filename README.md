# CSS Specificity Issue with :hover Pseudo-class

This repository demonstrates a common CSS issue related to the specificity of the `:hover` pseudo-class and unexpected inheritance.

## Problem
The `:hover` state on a parent element unintentionally overrides the `:hover` style of a child element due to specificity conflicts.

## Solution
Several approaches can be used to address this issue.  The most suitable approach will depend on the overall CSS structure and intended design.

One approach is to increase the specificity of the child's `:hover` selector to override the parent's `:hover` selector.
Another approach may involve restructuring the CSS to avoid the specificity conflict altogether.

The solution file (`bugSolution.css`) demonstrates how the specificity conflict has been resolved using a more specific selector for the child element.