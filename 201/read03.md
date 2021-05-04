# HTML Lists, CSS Boxes, JS Control Flow

## Lists

>There are lots of occasions when we need to use lists. HTML provides us with three different types:
>
>* Ordered lists are lists where each item in the list is numbered. For example, the list might be a set of steps for a recipe that must be performed in order, or a legal contract where each point needs to be identified by a section number.
>* Unordered lists are lists that begin with a bullet point (rather than characters that indicate order).
>* Definition lists are made up of a set of terms along with the definitions for each of those terms.
>- Jon Duckett



### Ordered Lists

You first have to write an `<ol>` element.
And then for each list item you'd have to create `<li>` element.
Example:

```
<ol>
    <li>Chop potatoes into quarters</li>
    <li>Simmer in salted water for 15-20
        minutes until tender</li>
    <li>Heat milk, butter and nutmeg</li>
    <li>Drain potatoes and mash</li>
    <li>Mix in the milk mixture</li>
</ol>
```

and this would appear like this:

<ol>
    <li>Chop potatoes into quarters</li>
    <li>Simmer in salted water for 15-20
        minutes until tender</li>
    <li>Heat milk, butter and nutmeg</li>
    <li>Drain potatoes and mash</li>
    <li>Mix in the milk mixture</li>
</ol>

### Unordered Lists

This is the same as ordered lists, you just write `<ul>` instead of `<ol>`.
And then for each list item you'd have to create `<li>` element.
Example:

```
<ul>
    <li>1kg King Edward potatoes</li>
    <li>100ml milk</li>
    <li>50g salted butter</li>
    <li>Freshly grated nutmeg</li>
    <li>Salt and pepper to taste</li>
</ul>
```
Which would appear as:

<ul>
    <li>1kg King Edward potatoes</li>
    <li>100ml milk</li>
    <li>50g salted butter</li>
    <li>Freshly grated nutmeg</li>
    <li>Salt and pepper to taste</li>
</ul>

### Definition Lists
These are a bit different, usually consists of a series of terms and their definitions.
You first create a `<dl>` element and Inside it put `<dt>`, which is the term being defined, and inside it you will usually put `<dd>`, which is the definition.
Example:

```
<dl>
    <dt>Sashimi</dt>
    <dd>Sliced raw fish that is served with
        condiments such as shredded daikon radish or
        ginger root, wasabi and soy sauce</dd>
    <dt>Scale</dt>
    <dd>A device used to accurately measure the
        eight of ingredients</dd>
    <dd>A technique by which the scales are removed
        from the skin of a fish</dd>
    <dt>Scamorze</dt>
    <dt>Scamorzo</dt>
    <dd>An Italian cheese usually made from whole
        cow's milk (although it was traditionally made
        from buffalo milk)</dd>
</dl>
```

Which would appear as:

<dl>
<dt>Sashimi</dt>
<dd>Sliced raw fish that is served with
condiments such as shredded daikon radish or
ginger root, wasabi and soy sauce</dd>
<dt>Scale</dt>
<dd>A device used to accurately measure the
weight of ingredients</dd>
<dd>A technique by which the scales are removed
from the skin of a fish</dd>
<dt>Scamorze</dt>
<dt>Scamorzo</dt>
<dd>An Italian cheese usually made from whole
cow's milk (although it was traditionally made
from buffalo milk)</dd>
</dl>

### Nested Lists

>You can put a second list inside an `<li>` element to create a sub-list or nested list.
>Browsers display nested lists indented further than the parent list. In nested unordered lists, the browser will usually change the style of the bullet point too.
>- Jon Duckett

Example:

```
<ul>
    <li>Mousses</li>
    <li>Pastries
        <ul>
            <li>Croissant</li>
            <li>Mille-feuille</li>
            <li>Palmier</li>
            <li>Profiterole</li>
        </ul>
    </li>
    <li>Tarts</li>
</ul>
```

Which would appear as:

<ul>
<li>Mousses</li>
<li>Pastries
<ul>
<li>Croissant</li>
<li>Mille-feuille</li>
<li>Palmier</li>
<li>Profiterole</li>
</ul>
</li>
<li>Tarts</li>
</ul>

## HTML Boxes

### Box Dimensions

Normally an HTML box is the size of it's contents. if you want to change the dimensions for a box you can use the `height` and `width` properties in CSS.

>Some page designs expand and shrink to fit the size of the user's screen. In such designs, the min-width property specifies the smallest size a box can be displayed at when the browser window is narrow, and the max-width property indicates the maximum width a box can stretch to when the browser window is wide.
>- Jon Duckett

Same with Height, you can use the `min-height` and `max-height` properties to set up the min and max sizes of a box.

### Overflowing Content

There's also the overflow property, which tells the
browser what to do if the content contained within a box is larger than the box itself. It can have one of two values:

#### hidden
This property simply hides any extra content that does not fit in the box.

#### scroll
his property adds a scrollbar to the box so that users can scroll to see the missing content.


## Borders And Margins

![example](https://i.imgur.com/tcyAOi8.png)


## JavaScript

### Arrays

An array is a special type of variable. It doesn't just store one value; it stores a list of values.
You probably should be using an array if you're working with a list or a set of values that are related to each other.
Creating arrays is pretty simple, as they're a data type, you just assign a variable to them.
Example:

```
var colors = ['white', 'black', ' custom '];
```

Values in an array are accessed as if they are in a numbered list. It is important to know that the numbering of this list starts at zero (not one).

Each item in an array is automatically given a number called an index. This can be used to access specific items in the
array. Consider the following array which holds three colors:

```
var colors;
colors= ['white',
'black',
'custom'];
```

Confusingly, index values start at 0 (not 1), so the following table shows items from the array and their corresponding index values:

```
  INDEX     VALUE
    0      'white'
    1      'black'
    2     'custom'
```

You can change items in an array, simply you just specify the array first, then in brackets `[]` right after it you put the index of what you want to change.

```
colors[2] = 'beige ' ;
```

This will change the `custom` value to that of a `beige` value.






<br/><br/> 
<br/><br/>  



|201| [Go back Home](https://suhaib-ersan.github.io/reading-notes/) |
|-|-|
| read## | Name and Link |
| read01 | [Introductory HTML and JavaScript](https://suhaib-ersan.github.io/reading-notes/201/read01) |
| read02 | [HTML Text, CSS Introduction, and Basic JavaScript Instructions](https://suhaib-ersan.github.io/reading-notes/201/read02) |
| **read03** | **HTML Lists, CSS Boxes, JS Control Flow** |
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