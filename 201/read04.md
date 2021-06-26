# HTML Links, CSS Layout, JS Functions

## Links

>Links are created using the `<a>` element. Users can click on anything between the opening `<a>` tag and the closing `</a>` tag. You specify which page you want to link to using the href attribute.
>- Jon Duckett

This can include the text, the backgrounds, any buttons or borders and similar.

### Linking to Pages on The Same Site

This can be done by specifying the `href` attribute to be the path to that pages HTML file.
Example:


```
<p>
    <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="about-us.html">About</a></li>
        <li><a href="movies.html">Movies</a></li>
        <li><a href="contact.html">Contact</a></li>
    </ul>
</p
```

### Relatie URLs

These can be used to link to pages within your own website, they are an easier way to write the URL.

### Opening Links in a New Window

This can achieved using the `target` attribute, and by assigning a value of `"_blank"` to it.

## Layout

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


## Functions

### What is a function?

>Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of statements).
>- Jon Duckett

Functions make your code easier to read, and make sense. also makes editing the code easier as you only have to edit one function instead of 10+ blocks of code.


<br/><br/> 
<br/><br/>  



|201| [Go back Home](https://suhaib-ersan.github.io/reading-notes/) |
|-|-|
| read## | Name and Link |
| read01 | [Introductory HTML and JavaScript](https://suhaib-ersan.github.io/reading-notes/201/read01) |
| read02 | [HTML Text, CSS Introduction, and Basic JavaScript Instructions](https://suhaib-ersan.github.io/reading-notes/201/read02) |
| read03 | [HTML Lists, CSS Boxes, JS Control Flow](https://suhaib-ersan.github.io/reading-notes/201/read03) |
| **read04** | **HTML Links, CSS Layout, JS Functions** |
| read05 | [HTML Images; CSS Color & Text](https://suhaib-ersan.github.io/reading-notes/201/read05) |
| read06 | [JS Object Literals; The DOM](https://suhaib-ersan.github.io/reading-notes/201/read06) |
| read07 | [HTML Tables; JS Constructor Functions](https://suhaib-ersan.github.io/reading-notes/201/read07) |
| read08 | [More CSS Layout](https://suhaib-ersan.github.io/reading-notes/201/read08) |
| read09 | [Forms and JS Events](https://suhaib-ersan.github.io/reading-notes/201/read09) |
| read10 | [Debugging](https://suhaib-ersan.github.io/reading-notes/201/read10) |
| read11 | [Audio, Video, Images](https://suhaib-ersan.github.io/reading-notes/201/read11) |
| read12 | [Docs for the HTML `<canvas>` Element & Chart.js](https://suhaib-ersan.github.io/reading-notes/201/read12) |
| read13 | [Local Storage](https://suhaib-ersan.github.io/reading-notes/201/read13) |
| read14 | [](https://suhaib-ersan.github.io/reading-notes/201/read14) |
| read15 | [](https://suhaib-ersan.github.io/reading-notes/201/read15) |