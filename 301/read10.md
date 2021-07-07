# In memory storage

* What is a ‘call’?

function invocation.


&nbsp;


* How many ‘calls’ can happen at once?

one, since the javascript engine is single-threaded.


&nbsp;


* What does LIFO mean?

Last In, First Out (LIFO), which temporarily stores and manages function invocation (call), and solves the last function that was called .

&nbsp;


* Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.


to get this error in console 

![error message](https://i.imgur.com/kQ6XHy5.png)

will look like this 

```
function firstFunction(){
  throw new Error('Stack Trace Error');
}

function secondFunction(){
  firstFunction();
}

function thirdFunction(){
  secondFunction();
}

thirdFunction();
```


&nbsp;


* What causes a Stack Overflow?

a function that calls itself without an exit point.

&nbsp;


<hr />


<br />

* What is a ‘reference error’?

It's when you try to reference something that wasn't declared yet.


&nbsp;


* What is a ‘syntax error’?

this occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.


&nbsp;


* What is a ‘range error’?

Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.

&nbsp;


* What is a ‘type error’?

this types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

&nbsp;


* What is a breakpoint?

It's where the code will stop when you are debugging it.

&nbsp;


* What does the word ‘debugger’ do in your code?

add a breakpoint.

&nbsp;



<br/><br/> 
<br/><br/> 



|301| [Home](https://suhaib-ersan.github.io/reading-notes/) |
|-|-|
| read01 | [Introduction to React and Components](https://suhaib-ersan.github.io/reading-notes/301/read01) |
| read02 | [State and Props](https://suhaib-ersan.github.io/reading-notes/301/read02) |
| read03 | [Passing Functions as Props](https://suhaib-ersan.github.io/reading-notes/301/read03) |
| read04 | [React and Forms](https://suhaib-ersan.github.io/reading-notes/301/read04) |
| read05 | [Putting it all together](https://suhaib-ersan.github.io/reading-notes/301/read05) |
| read06 | [NODE.JS](https://suhaib-ersan.github.io/reading-notes/301/read06) |
| read07 | [REST](https://suhaib-ersan.github.io/reading-notes/301/read07) |
| read08 | [APIs](https://suhaib-ersan.github.io/reading-notes/301/read08) |
| read09 | [FUNCTIONAL PROGRAMMING](https://suhaib-ersan.github.io/reading-notes/301/read09) |
| read10 | **In memory storage** |
| read11 | [Authentication](https://suhaib-ersan.github.io/reading-notes/301/read11) |
| read12 | [Mongo and Mongoose](https://suhaib-ersan.github.io/reading-notes/301/read12) |
| read13 | [CRUD](https://suhaib-ersan.github.io/reading-notes/301/read13) |
| read14 | [Project Ideas](https://suhaib-ersan.github.io/reading-notes/301/read14) |
| read15 | [Project Kickoff](https://suhaib-ersan.github.io/reading-notes/301/read15) |