# udx-css-complete-guide

## Basics

### Styling Elements

- Inline styles, directly on an element, hard to mantain, an anti-pattern
- Internal, style is defined inside a `style` tag in the `head` section
- External, references an external css file, allows file caching

### Selectors

Indicates which elements in the DOM a style should be applied to

- Universal selector `*`
- Tag and pseudo elements selector
- Class, pseudo class and attribute selectors
- ID selector
- Inline style

### Core Concepts

- Cascading: multiple rules can be applied to the same element
- Specificity: resolves conflicts from multiple rules
- Inheritance: elements inherit styles from their parents

Note: Inheritance with body selector is good for font size font family

### Combinators

Help to be more precise by combining selectors

- Adjacent sibling (+): 2nd element comes directly after the 1st one and share same parent
- General sibling (~): 2nd element comes (not directly) after the 1st one and share same parent
- Child (>): 2nd element is a direct child of the first one
- Descendant ([space]): 2nd is a descendant of the 1st one
