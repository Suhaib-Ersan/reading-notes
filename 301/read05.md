# Putting it all together




&nbsp;


* How would you break a mock into a component heirarchy?

The first thing you’ll want to do is to draw boxes around every component (and subcomponent) in the mock and give them all names.

&nbsp;


* What is the single responsibility principle and how does it apply to components?

a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.

&nbsp;


* What does it mean to build a ‘static’ version of your application?

it's to build a version that takes your data model and renders the UI but has no interactivity.

&nbsp;


* Once you have a static application, what do you need to add?

interactivity.

&nbsp;


* What are the three questions you can ask to determine if something is state?

  * Is it passed in from a parent via props? If so, it probably isn’t state.
  * Does it remain unchanged over time? If so, it probably isn’t state.
  * Can you compute it based on any other state or props in your component? If so, it isn’t state.

&nbsp;


* How can you identify where state needs to live?

  * Identify every component that renders something based on that state.
  * Find a common owner component (a single component above all the components that need the state in the hierarchy).
  * Either the common owner or another component higher up in the hierarchy should own the state.
  * If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

<br/><br/> 
<br/><br/> 



|301| [Home](https://suhaib-ersan.github.io/reading-notes/) |
|-|-|
| read01 | [Introduction to React and Components](https://suhaib-ersan.github.io/reading-notes/301/read01) |
| read02 | [State and Props](https://suhaib-ersan.github.io/reading-notes/301/read02) |
| read03 | [Passing Functions as Props](https://suhaib-ersan.github.io/reading-notes/301/read03) |
| read04 | [React and Forms](https://suhaib-ersan.github.io/reading-notes/301/read04) |
| read05 | **Putting it all together** |
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
