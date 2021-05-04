# HTML Text, CSS Introduction, and Basic JavaScript Instructions

## Text

### Headings

HTML has six levels of headings levels, `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>` and `<h6>`, by default, the higher the number the smaller and lighter the text
For example:

<br/><br/> 

<h1>This is a level 1 Heading</h1>
<h2>This is a level 2 Heading</h2>
<h3>This is a level 3 Heading</h3>
<h4>This is a level 4 Heading</h4>
<h5>This is a level 5 Heading</h5>
<h6>This is a level 6 Heading</h6>

<br/><br/> 

### Paragraphs

To create paragraphs in HTML, you'd usually use the `<p>` tag by default, a browser will show each paragraph on a new line with some space between it and any subsequent paragraphs.

### Line Breaks And Horizontal Rules

#### the <br /> tag
the browser will automatically show each new paragraph or heading on a new line. But if you wanted to add a line break inside the middle of a paragraph you can use the line break tag `<br />` and that will add a space between lines.

#### the <hr /> tag

To create a break between themes — such as a change of topic in a book or a new scene in a play — you can add a horizontal rule between sections using the `<hr />` tag.

Let me demonstrate:
<hr />


## CSS

CSS is used to "style" your pages, like adding colors, borders, margins, paddings and changing text size, and others.
The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element.
CSS allows you to create rules that control the way that each individual box (and the contents of that box) is presented.

CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be  is played. A CSS rule contains two parts: a selector and a declaration.
Another one is 

You can add CSS to your HTML using three ways, one of them is called `inline`, which as the name suggests, is inline in a tag as an attribute, usually something like `style="blahblah"` and this will give this tag some styling, this method however, is deprecated as it's much harder and much more time consuming to edit those styles.

Another one is is called `internal`, which is styling that is in the HTML file, but is place inside the head element.

usually looks something like this

```
<head>
    <title>Using Internal CSS</title>
    <style type="text/css">
        body {
            font-family: arial;
            background-color: rgb(185,179,175);}
        h1 {
            color: rgb(255,255,255);}
    </style>
</head>
```

This way is much better than the inline one, but this is usually not used in favor of the better one, which is the `external` way.

The external CSS way, as the name suggests, is using an external source other than than the HTML to style the page, which is usually an external CSS file. This is achieved by putting a `<link>` tag inside the head.
Example:

```
<head>
    <title>Using External CSS</title>
    <link href="css/styles.css" type="text/css"
        rel="stylesheet" />
</head>
```


## JavaScript

### Statements

A script is a series of instructions that a computer can follow one-by-one.
Each individual instruction or step is known as a statement.
Statements should end with a semicolon.

### Comments

You should write comments to explain what your code does.
They help make your code easier to read and understand.
This can help you and others who read your code.

### Variables

A script will have to temporarily store the bits of information it needs to do its job. It can store this data in variables.
But how do you use and declare them?
it's pretty simple, you just write `var carNumber = 10;` and now you have a variable by the name of carNumber, that has a value of `10`.


### Data Types

JavaScript distinguishes between numbers, strings (which is text), and true or false values known as Booleans.




<br/><br/> 
<br/><br/>  



|201| [Go back Home](https://suhaib-ersan.github.io/reading-notes/) |
|-|-|
| read## | Name and Link |
| read01 | [Introductory HTML and JavaScript](https://suhaib-ersan.github.io/reading-notes/201/read01) |
| **read02** | **HTML Text, CSS Introduction, and Basic JavaScript Instructions** |
| read03 | [HTML Lists, CSS Boxes, JS Control Flow](https://suhaib-ersan.github.io/reading-notes/201/read03) |
| read04 | [HTML Links, CSS Layout, JS Functions](https://suhaib-ersan.github.io/reading-notes/201/read04) |
| read05 | [HTML Images; CSS Color & Text](https://suhaib-ersan.github.io/reading-notes/201/read05) |
| read06 | [JS Object Literals; The DOM](https://suhaib-ersan.github.io/reading-notes/201/read06) |
| read07 | [HTML Tables; JS Constructor Functions](https://suhaib-ersan.github.io/reading-notes/201/read07) |
| read08 | [More CSS Layout](https://suhaib-ersan.github.io/reading-notes/201/read08) |
| read09 | [](https://suhaib-ersan.github.io/reading-notes/201/read09) |
| read10 | [](https://suhaib-ersan.github.io/reading-notes/201/read10) |
| read11 | [](https://suhaib-ersan.github.io/reading-notes/201/read11) |
| read12 | [](https://suhaib-ersan.github.io/reading-notes/201/read12) |
| read13 | [](https://suhaib-ersan.github.io/reading-notes/201/read13) |
| read14 | [](https://suhaib-ersan.github.io/reading-notes/201/read14) |
| read15 | [](https://suhaib-ersan.github.io/reading-notes/201/read15) | 