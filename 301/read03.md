# Passing Functions as Props

## Reading

What does `.map()` return?

An array.

&nbsp;


* If I want to loop through an array and display each value in JSX, how do I do that in React?

Using `.map()`, we make every value in the array we are mapping go through html-like code we want it in.

&nbsp;


* Each list item needs a unique ____.

Key.

&nbsp;


* What is the purpose of a key?

Keys help React identify which items have changed, are added, or are removed.

&nbsp;


* What is the spread operator?

he spread syntax “spreads” the array into separate arguments.

&nbsp;


* List 4 things that the spread operator can do.

  * Copying an array
  * Concatenating or combining arrays
  * Using Math functions
  * Using an array as arguments

&nbsp;


* Give an example of using the spread operator to combine two arrays.

```
const hello = ['hello']
const world = ['world']

const helloWorld = [...hello,...world]
console.log(...helloWorld) // hello world
```

&nbsp;


* Give an example of using the spread operator to add a new item to an array.

```
const fruit1  = ['apple', 'pineapple', 'banana']
const fruit2 = ['orange']

const fruits = [...fruit1,...fruit2]
console.log(...fruits) // apple pineapple banana orange
```

&nbsp;


* Give an example of using the spread operator to combine two objects into one.

const hello = {hello: "hayoo"}
const world = {world: "globe"}

const helloWorld = {...hello,...world}
console.log(helloWorld) // Object { hello: "hayoo", world: "globe" }

## Videos

* In the video, what is the first step that the developer does to pass functions between components?

make a constructor.

&nbsp;


* In your own words, what does the increment function do?

Increase the number besides the names the instructor used.

&nbsp;


* How can you pass a method from a parent component into a child component?

By passing it as an attribute through the html-like code (example: `increment={this.increment}`).

&nbsp;


* How does the child component invoke a method that was passed to it from a parent component?

You can call it through `this.props.increment()`.


<br/><br/> 
<br/><br/> 



|301| [Home](https://suhaib-ersan.github.io/reading-notes/) |
|-|-|
| read01 | [Introduction to React and Components](https://suhaib-ersan.github.io/reading-notes/301/read01) |
| read02 | [State and Props](https://suhaib-ersan.github.io/reading-notes/301/read02) |
| read03 | **Passing Functions as Props** |
| read04 | [React and Forms](https://suhaib-ersan.github.io/reading-notes/301/read04) |
| read05 | [Putting it all together](https://suhaib-ersan.github.io/reading-notes/301/read05) |
| read06 | [NODE.JS](https://suhaib-ersan.github.io/reading-notes/301/read06) |
| read07 | [REST](https://suhaib-ersan.github.io/reading-notes/301/read07) |
| read08 | [APIs](https://suhaib-ersan.github.io/reading-notes/301/read08) |
| read09 | [FUNCTIONAL PROGRAMMING](https://suhaib-ersan.github.io/reading-notes/301/read09) |
| read10 | [In memory storage](https://suhaib-ersan.github.io/reading-notes/301/read10) |
| read11 | [Authentication](https://suhaib-ersan.github.io/reading-notes/301/read11) |
| read12 | [Mongo and Mongoose](https://suhaib-ersan.github.io/reading-notes/301/read12) |
| read13 | [CRUD](https://suhaib-ersan.github.io/reading-notes/301/read13) |
| read14 | [Project Ideas](https://suhaib-ersan.github.io/reading-notes/301/read14) |
| read15 | [Project Kickoff](https://suhaib-ersan.github.io/reading-notes/301/read15) |