# Forms and JS Events

## Form Controls 

There are several types of form controls that you can use to collect information from visitors to your site.

### Adding Text:
* Text input (single-line): Used for a single line of text such as email addresses and names
* Password input: Like a single line text box but it masks the characters entered.
* Text area (multi-line): For longer areas of text, such as messages and comments.
* 

### Making Choices:
* Radio buttons: For use when a user must select one of a number of options.
* Checkboxes: When a user can select and unselect one or more options.
* Drop-down boxes: When a user must pick one of a number of options from a list.

### Submitting Forms:
* Submit buttons: To submit data from your form to another web page.
* Image buttons: Similar to submit buttons but they allow you to use an image.

## Form Structure

* Form controls live inside a `<form>` element. This element should always carry the action attribute and will usually have a method and id attribute too.

* `action`: Every `<form>` element requires an action attribute. Its value is the URL for the page on the server that will receive the information in the form when it is submitted.

* `method`: Forms can be sent using one of two methods: get or post.

### Text Input

* `<input>` element is used to create several different form controls. The value of the type attribute determines what kind of input they will be creating.

* `type="text"`: When the type attribute has a value of text, it creates a single line text input.

* `name`: When users enter information into a form, the server needs to know which form control each piece of data was entered into. (For example, in a login form, the server needs to know what has been entered as the username and what has been given as the password.) Therefore, each form control requires a name attribute. The value of this attribute identifies the form control and is sent along with the information they enter to the server.

* `maxlength`: You can use the maxlength attribute to limit the number of characters a user may enter into the text field. Its value is the number of characters they may enter. For example, if you were asking for a year, the maxlength attribute could have a value of 4.

### Submit Button

* `type="submit"` The submit button is used to send a form to the server.
* `name`: It can use a name attribute but it does not need to have one.
* `value`: The value attribute is used to control the text that appears on a button. It is a good idea to specify the words you want to appear on a button because the default value of buttons on some browsers is ‘Submit query’ and this might not be appropriate for all kinds of form.

Different browsers will show submit buttons in different ways and tend to fit the visual presentation of the browser. If you want to control the appearance of a submit button, you can either use CSS, or you can use an image for the button.

### Grouping Form Elements

* `<fieldset>`: You can group related form controls together inside the `<fieldset>` element. This is particularly helpful for longer forms.

Most browsers will show the fieldset with a line around the edge to show how they are related. The appearance of these
lines can be adjusted using CSS.

* `<legend>`: The `<legend>` element can come directly after the opening `<fieldset>` tag and contains a caption which helps identify the purpose of that group of form controls.

# Lists, Tables and Forms

## Bullet Point Styles

The `list-style-type` property allows you to control the shape or style of a bullet point (also known as a marker).

### Unordered Lists
For an unordered list you can use the following values: none, disc, circle, square.


### Ordered Lists
For an ordered (numbered) list you can use the following values: decimal, decimal-leading-zero, lower-alpha, upper-alpha, lower-roman, upper-roman.


## Positioning the Marker

Lists are indented into the page by default and the list-style position property indicates whether the marker should
appear on the inside or the outside of the box containing the main points.
This property can take one of two values: 

### outside
The marker sits to the left of the block of text. (This is the default behavior if this property is not used.)

### inside
The marker sits inside the box of text (which is indented). In the example shown, the width of the list has been limited to 150 pixels. This ensures that the text wraps onto a new line so you can see how the value of inside sits the bullet inside the first line of text.




# Events

When you browse the web, your browser registers different types of events. It's the browser's way of saying, "Hey, this just happened." Your script can then respond to these events.
Scripts often respond to these events by updating the content of the web page (via the Document Object Model) which makes the page feel more interactive. In this chapter, you will learn how:

## Different Event Types

Here is a selection of the events that occur in the browser while you are browsing the web. Any of these events can be used to trigger a function in your JavaScript code.
### UI Events:
Occur when a user interacts with the browser's user interface (UI) rather than the web page.

| Event | Description |
|-|-|
| load | Web page has finished loading |
| unload | Web page is unloading (usually because a new page was requested) |
| error | Browser encounters a JavaScript error or an asset doesn't exist |
| resize | Browser window has been resized |
| scroll | User has scrolled up or down the page |


### Keyboard Events:
Occur when a user interacts with the keyboard (see also input event).

| Event | Description |
|-|-|
keydown User first presses a key (repeats while key is depressed) |
keyup User releases a key |
keypress Character is being inserted (repeats while key is depressed) |

### Mouse Events:
Occur when a user interacts with a mouse. trackpad, or touchscreen.

| Event | Description |
|-|-|
| click | User presses and releases a button over the same element |
| dblclick | User presses and releases a button twice over the same element |
| mouseddown | User presses a mouse button while over an element |
| mouseup | User releases a mouse button while over an element |
| mousemove | User moves the mouse (not on a touchscreen) |
| mouseover | User moves the mouse over an element (not on a touchscreen) |
| mouseout | User moves the mouse off an element (not on a touchscreen) |
















<br/><br/> 
<br/><br/>  



|201| [Go back Home](https://suhaib-ersan.github.io/reading-notes/) |
|-|-|
| read## | Name and Link |
| read01 | [Introductory HTML and JavaScript](https://suhaib-ersan.github.io/reading-notes/201/read01) |
| read02 | [HTML Text, CSS Introduction, and Basic JavaScript Instructions](https://suhaib-ersan.github.io/reading-notes/201/read02) |
| read03 | [HTML Lists, CSS Boxes, JS Control Flow](https://suhaib-ersan.github.io/reading-notes/201/read03) |
| read04 | [HTML Links, CSS Layout, JS Functions](https://suhaib-ersan.github.io/reading-notes/201/read04) |
| read05 | [HTML Images; CSS Color & Text](https://suhaib-ersan.github.io/reading-notes/201/read05) |
| read06 | [JS Object Literals; The DOM](https://suhaib-ersan.github.io/reading-notes/201/read06) |
| read07 | [HTML Tables; JS Constructor Functions](https://suhaib-ersan.github.io/reading-notes/201/read07)) |
| read08 | [More CSS Layout](https://suhaib-ersan.github.io/reading-notes/201/read08) |
| **read09** | **Forms and JS Events** |
| read10 | [Debugging](https://suhaib-ersan.github.io/reading-notes/201/read10) |
| read11 | [Audio, Video, Images](https://suhaib-ersan.github.io/reading-notes/201/read11) |
| read12 | [Docs for the HTML <canvas> Element & Chart.js](https://suhaib-ersan.github.io/reading-notes/201/read12) |
| read13 | [](https://suhaib-ersan.github.io/reading-notes/201/read13) |
| read14 | [](https://suhaib-ersan.github.io/reading-notes/201/read14) |
| read15 | [](https://suhaib-ersan.github.io/reading-notes/201/read15) |