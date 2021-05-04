# Read: 08 - More CSS Layout

### Building Blocks

CSS gives HTML elements something akin to a box, this box is either `block-level` or an `inline-level`.


Block-level boxes start on a new line, while inline (as the name suggests) stays on the same line, and doesn't start a new one.

### Containing Elements

When a block-level element sits inside another, the outer one will be known as a "parent" or a "containing" element.

### Controlling the Position of Elements

CSS has a few ways to control the layout of the page, which can be specified using the `position` property in CSS, there is also `float` which can be used to float element.

#### Normal Flow

Every block-level elements appears on a new line, normally no two or more block-levels elements stay at the same line.

#### Relative Positioning

This one is the same as the normal flow, but has a key difference, which is that you can control the elements position using the `top` or `left` or similar properties, this will make the element move however you specify, this however won't change the positioning of other element.

#### Absolute Positioning

This one makes the element position relative to the to its containing element, normal flow elements will ignore this one when positioning themselves.

#### Fixed Positioning

This is the same as Absolute Positioning but it's relative to the browsers window and not to it's containing element.

#### Floating Elements

> Floating an element allows you to take that element out of normal flow and position it to the far left or right of a containing box. The floated element becomes a block-level element around which other content can flow. Jon Duckett

### Fixed Width layouts

This layout controlling way doesn't change the size of elements and boxes in a site with how big the screen you're viewing it on, this is by and large an old way of doing websites. 

### Liquid Layouts

Liquid layouts change and stretch or contract when the user makes their screen bigger or smaller, and they tend to use percentages.

