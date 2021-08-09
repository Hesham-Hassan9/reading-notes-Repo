# Layout
### Key Concepts in Positioning Elements
* Building Blocks: CSS treats each HTML element as if it were in its own box. This square will either be a block-level square or an inline square.
* Block level items: start on a new line
* Inline elements: flow between surrounding text

* Containing Elements: If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.

**Control the position of elements:** CSS contains the following positioning systems that allow you to control the layout of the page: normal flow, relative position, and absolute position. You can specify the GPS using the location property in CSS. You can also float items using the float feature.

### Normal Flow:
position: fixed: In a normal flow, each block-level element sits on top of the next. Since this is the default way browsers handle HTML elements, you don't need a CSS property to indicate that the elements should appear in the normal flow, but the syntax would be: position: static;

### Relative positioning:
Position: Relative: Relative position moves an element in relation to where it would have been in a normal flow. For example, you can move it 10 pixels less than it would in normal flow or 20% to the right.

### Absolute positioning:
position: absolute: When the position property is given an absolute value, the square is taken out of the normal flow and no longer affects the position of other elements on the page. (They act like it doesn't exist.)

### Fixed positioning:
position: fixed: position: fixed position is a type of absolute position that requires the center property to have a fixed value.

### nested elements:
z-index: position: When using a relative, fixed, or absolute positioning, the boxes can overlap. If the boxes overlap, the elements that appear later in the HTML code are on top of the elements previously on the page.

**CSS Frameworks:** CSS frameworks aim to make your life easier by providing code for common tasks, such as creating layout grids, design models, creating print-friendly versions of pages, etc. You can include CSS framework code in your projects instead of writing CSS from scratch.

Dives are often used as containing elements to group page sections together. Browsers render pages in the normal flow unless you specify a relative, absolute, or fixed position. Float moves content to the left or right of the page and can be used to create multi-column layouts. (Floating elements require a specific width.) Pages can be either fixed width or fluid (extendable) layouts. Designers keep pages 960-1000px wide, and indicate what the site is about within the top 600px (to prove it fits without scrolling). Grids help create professional and flexible designs. CSS Frameworks provide rules for common tasks. You can include multiple CSS files on one page