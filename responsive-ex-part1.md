### What is an em?

An `em` is a relative unit of measurement based on the default font size of an element. This lets us set set properties involving length to be relative to the font size.

### What is the difference between em and rem?

A `rem`'s size is relative to the `html` element. This means that `1rem` corresponds to the same size everywhere on the page. An `em`'s size is relative to the immediate element's default font size.

### What is mobile-first design?

Mobile first design is a design approach that emphasizes mobile display sizes before laptop or desktop display sizes. CSS is tailored first for small viewports and additional styles and other overrides for larger screens are added via media queries.

### What is BEM?

Block Element Modifier is an organizational pattern for structuring CSS that results in modular, reusable CSS code that is easier to maintain. It is particularly helpful for larger projects.

A BLOCK is a standalone entity that is meaningful on its own (ex: `header`, `container`, `menu`, `input`, `checkbox`).

An ELEMENT is part of a block that has no standalone meaning and is semantically tied to the block (ex: `menu item` , `list item`, `checkbox caption`, `header title`).

A MODIFIER is a flag on a block or element. These change appearance or behavior (ex: `disabled`, `highlighted`, `checked`, `fixed`, `size big`, `color yellow`).
