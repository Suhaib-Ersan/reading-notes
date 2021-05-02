# Read: 06 - JS Object Literals; The DOM

## JS Object Literals

### What is an object in JS?

> Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. - Jon Duckett

And in objects, variables become properties, and functions becomes methods. And the names of those variables or functions become known as a key.

There a few ways of creating objects, the easiest and most popular one is called a `Literal Notation`. To create object using this way, you first declare a variable, then inside the variable you put curly braces `{}`, inside those curly braces is the object.
We could also create objects using what's called `Constructor Notation`, to create an object using this method, you'd first have to declare a variable, then inside that variable add `new Object();` which creates a blank object.

To access objects, we have a few options, like:
`var varName = objectName.propertyOrMethodName`, which is called the dot notation. Example:

```
var hotelName = hotel.name;
```

Or we can use:
`var varName = objectName['propertyOrMethodName'];` which is the brackets way, but this way doesn't allow you to access methods inside the objects. Example:

```
var hotelName = hotel['name'];
```

You can also update the values of objects, to do that you have to do:
use the dot notation or the square brackets way, and if you want to delete a property, you can use the `delete` keyword. 


## DOM

### What is DOM?

DOMs, or Document Object Model, is:

> The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window. - Jon Duckett

The DOM isn't HTML, and it's not JavaScript, so what is it? it's a set of rules that all major browsers use.
DOM is an API, or an Application Programming Interface, which is a way for programs to communicate with each other, a translator, if you will.
