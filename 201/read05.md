# HTML Images; CSS Color & Text

## Images

Images are important to websites, as they draw your attention and help set the mood, so it's important to choose good photos as well as choosing a correct format.
Its good practice to store your site images in a separate folder, usually called "img" or "images" or "assets", this is to keep things tidy instead of a mess of files on top of each other.

### Adding images to HTML

Adding images to HTML is pretty simple, it's done by using the `<img>` tag, and then adding a source, and a few attributes if you choose to.
Example:

```
<img src="images/quokka.jpg" alt="A family of quokka" title="The quokka is an Australian marsupial that is similar in size to the domestic cat." />
```
> example from Jon Ducketts HTML book

The `src="xxx"` attribute is the most important one, as it's the one which sets what and where to get the image from. The `alt` attribute lets you put placeholder text that will appear when the image fails to load for whatever reason. The `title` attribute lets you provide additional information about the image, Most browsers will display the content of this attribute in a tooltip when the user hovers over the image.

### Image formats

You should use the `.jpg` or `.jpeg` format whenever possible, as it allows you to use compressed images that don't take long to load, but also don't look too bad (although that depends on the level of compression), one if it's other drawbacks is that it doesn't allow transparency or what's known as the alpha channel (allows pixel to not exist, e.g. transparent).

The `.gif` format is an old one that refuses to die, although it has many limitations and is old code, it's still immensely popular on the web. This format allows you to post short video clips without audio, thought you usually you can't fast forward or backward in a gif, one of it's widespread limitations, it's colors reproduction is also quite limited, as it can usually allow only up to 256 colors (compared to other formats which allow the full 16.7+ or more colors, depending on the compression), gifs usually also have bigger-than-expected sizes which happens because of it's old code.

Lastly, the `.png` format, which is a lossless format, meaning it doesn't change the pixels colors when it compresses them, which is different from what `.jpg` and `.gif` do, it also allows transparency (which `.jpg` doesn't), it's a great format except for it's size, as it's size can be much larger than other lossy formats such as `.jpeg`. As such `.png` should only be used when you require a high quality image and/or transparency.

### Image resolution 

Images are created from things we call `pixels`, which are tiny squares that are made up of three values, a `Red` color value and a `Green` color value and lastly a `Blue` color value (commonly known as RGB), each one has a number, the higher it is the stronger the color and the further it is from black, and if all of them are high then the closer the result will be to white. The value can usually be from 0 to 256 (when working on an 8bit image, which is by far the most common).


### Vector images

Vector images differ from bitmap images and are resolution-independent. Vector images are commonly created in programs such as Adobe Illustrator.
Vector images are created by placing points on a grid, and drawing lines between those points. A color can then be added to "fill in" the lines that have been created. The advantage of creating line drawings in vector format is that you can increase the dimensions of the image without affecting the quality of it.

## Color

The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways:

### RGB Values

These express colors in terms of how much red, green and blue are used to make it up. For example: rgb(100,100,90).

### HEX Codes

These are six-digit codes that represent the amount of red, green and blue in a color,
preceded by a pound or hash # sign. For example: #ee3e80.

### Color Names

There are 147 predefined color names that are recognized by browsers. For example: DarkCyan.

## Text

### Typeface Terminology

#### Serif

Serif fonts have extra details on the ends of the main strokes of the letters. These details are known as serifs. In print, serif fonts were traditionally used for long passages of text because they were considered easier to read.

#### Sans-Serif

Sans-serif fonts have straight ends to letters, and therefore have a much cleaner design. Screens have a lower resolution than print. So, if the text is small, sans-serif fonts can be clearer to read.

#### Monospace

Every letter in a monospace (or fixed-width) font is the same width. (Non-monospace fonts have different widths.) Monospace fonts are commonly used for code because they align nicely, making the text easier to follow.


### Specifying Typefaces

The font-family property allows you to specify the typeface that should be used for any text inside the element(s) to
which a CSS rule applies. The value of this property is the name of the typeface you want to use. The people who are visiting your site need the typeface you have specified installed on their computer in order for it to be displayed.
You can specify a list of fonts separated by commas so that, if the user does not have your first choice of typeface installed, the browser can try to use an alternative font from the list. It is also common to end with a generic font name for that type of font.






<br/><br/> 
<br/><br/>  



|201| [Go back Home](https://suhaib-ersan.github.io/reading-notes/) |
|-|-|
| read## | Name and Link |
| read01 | [Introductory HTML and JavaScript](https://suhaib-ersan.github.io/reading-notes/201/read01) |
| read02 | [HTML Text, CSS Introduction, and Basic JavaScript Instructions](https://suhaib-ersan.github.io/reading-notes/201/read02) |
| read03 | [HTML Lists, CSS Boxes, JS Control Flow](https://suhaib-ersan.github.io/reading-notes/201/read03) |
| read04 | [HTML Links, CSS Layout, JS Functions](https://suhaib-ersan.github.io/reading-notes/201/read04) |
| **read05** | **HTML Images; CSS Color & Text** |
| read06 | [JS Object Literals; The DOM](https://suhaib-ersan.github.io/reading-notes/201/read06) |
| read07 | [HTML Tables; JS Constructor Functions](https://suhaib-ersan.github.io/reading-notes/201/read07) |
| read08 | [More CSS Layout](https://suhaib-ersan.github.io/reading-notes/201/read08) |
| read09 | [Forms and JS Events](https://suhaib-ersan.github.io/reading-notes/201/read09) |
| read10 | [Debugging](https://suhaib-ersan.github.io/reading-notes/201/read10) |
| read11 | [Audio, Video, Images](https://suhaib-ersan.github.io/reading-notes/201/read11) |
| read12 | [Docs for the HTML <canvas> Element & Chart.js](https://suhaib-ersan.github.io/reading-notes/201/read12) |
| read13 | [](https://suhaib-ersan.github.io/reading-notes/201/read13) |
| read14 | [](https://suhaib-ersan.github.io/reading-notes/201/read14) |
| read15 | [](https://suhaib-ersan.github.io/reading-notes/201/read15) |