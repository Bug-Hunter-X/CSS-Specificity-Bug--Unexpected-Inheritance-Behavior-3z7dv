# CSS Specificity Bug: Unexpected Inheritance Behavior

This repository demonstrates an uncommon CSS bug related to specificity and inheritance. The bug showcases a scenario where a seemingly targeted CSS rule is overridden by a more specific selector, leading to unexpected styling outcomes.

## Bug Description

The bug lies in the unexpected behavior of CSS specificity. The `div p` selector, intended to style paragraphs within a div element, is unexpectedly overridden by the `p` selector due to its higher specificity.

## Bug Reproduction

1. Open `bug.css`.
2. Observe the CSS code and the unintended styling.
3. Run the HTML file associated with this CSS. (Not included here, but a simple HTML file with a div containing a p element would suffice)

## Solution

The solution involves understanding and adjusting CSS specificity to ensure the intended styling is applied.  This is addressed in `bugSolution.css`.

## How to Fix

To resolve the issue, increase the specificity of the `div p` selector to override the `p` selector. This can be done by adding an extra class or ID to the paragraph or adding more specificity to the div p selector.