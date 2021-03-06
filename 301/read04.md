# React and Forms

What is a ‘Controlled Component’?

It's one that takes its current value through props and notifies changes through callbacks like onChange. A parent component "controls" it by handling the callback and managing its own state and passing the new values as props to the controlled component.

&nbsp;


* Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

Update the state with their responses as soon as they enter them, because that allows us to keep the data for the user if they close the page by mistake or something similar.

&nbsp;


* How do we target what the user is entering if we have an event handler on an input field?

by calling a function each time this changes.

&nbsp;


* Why would we use a ternary operator?

if we want a quick way to choose between two options.

&nbsp;


* Rewrite the following statement using a ternary statement:


```
if(x===y){
 console.log(true);
} else {
 console.log(false);
}
```

you do that through: 

```
let o = x===y ? true : false;
console.log(o);
```

<br/><br/>
<br/><br/>

| 301    | [Home](https://suhaib-ersan.github.io/reading-notes/)                                           |
| ------ | ----------------------------------------------------------------------------------------------- |
| read01 | [Introduction to React and Components](https://suhaib-ersan.github.io/reading-notes/301/read01) |
| read02 | [State and Props](https://suhaib-ersan.github.io/reading-notes/301/read02)                      |
| read03 | [Passing Functions as Props](https://suhaib-ersan.github.io/reading-notes/301/read03)           |
| read04 | **React and Forms**                                                                             |
| read05 | [Putting it all together](https://suhaib-ersan.github.io/reading-notes/301/read05)              |
| read06 | [NODE.JS](https://suhaib-ersan.github.io/reading-notes/301/read06)                              |
| read07 | [REST](https://suhaib-ersan.github.io/reading-notes/301/read07)                                 |
| read08 | [APIs](https://suhaib-ersan.github.io/reading-notes/301/read08)                                 |
| read09 | [FUNCTIONAL PROGRAMMING](https://suhaib-ersan.github.io/reading-notes/301/read09)               |
| read10 | [In memory storage](https://suhaib-ersan.github.io/reading-notes/301/read10)                    |
| read11 | [Authentication](https://suhaib-ersan.github.io/reading-notes/301/read11)                       |
| read12 | [Mongo and Mongoose](https://suhaib-ersan.github.io/reading-notes/301/read12)                   |
| read13 | [CRUD](https://suhaib-ersan.github.io/reading-notes/301/read13)                                 |
| read14 | [Project Ideas](https://suhaib-ersan.github.io/reading-notes/301/read14)                        |
| read15 | [Project Kickoff](https://suhaib-ersan.github.io/reading-notes/301/read15)                      |
