# CSS :hover Pseudo-class Issue with Nested Elements

This repository demonstrates a common yet subtle issue with the CSS `:hover` pseudo-class selector when applied to nested elements.  The provided CSS code exhibits unexpected behavior where the hover effect does not propagate to child elements as intended.

The `bug.css` file contains the problematic code. The `bugSolution.css` file provides a corrected version and explanation.

**Problem:** The nested element's style does not change on parent hover.

**Solution:** The issue is resolved by using a more specific selector or adjusting the CSS structure to ensure the hover state applies correctly to the nested elements.  Refer to `bugSolution.css` for the corrected implementation.

This example highlights the importance of understanding CSS specificity and how selectors interact with nested elements.