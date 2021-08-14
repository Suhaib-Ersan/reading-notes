# Node Ecosystem, TDD, CI/CD


* Describe (in plain English) what Array.map() does

It does something to each item in an array, and then returns something (if you choose to do so, otherwise returns undefined) which allows you to make a new array after the changes from the whole process. 

&nbsp;

* Describe (in plain English) what Array.reduce() does

This function something to each item in an array, in this case a function of your choosing, but it also has something called an "accumulator" which is just a value that persists between function calls.

&nbsp;

* Provide code snippets showing how to use superagent() to fetch data from a URL and log the result

```
let urlRawData = superagent.get('url.com/here'); // not a real url
let data = urlRawData.body;
console.log(data); 
// expected result: a json file/object
```

&nbsp;

* With normal Promise .then() syntax


```
superagent.get('url.com/here') // not a real url
  .then( urlRawData => {
    let data = urlRawData.body;
    console.log(data);
  }) 
// expected result: a json file/object
```

&nbsp;

* Again with async / await syntax


```
async function getData () {
  let urlRawData = await superagent.get('url.com/here'); // not a real url
  let data = urlRawData.body;
  console.log(data);  
}
// expected result: a json file/object
```

&nbsp;

* Explain promises as though you were mentoring a Code 301 level student

They are just as they sound, the program "makes a promise" to a part of the code that "I'll get back to you once you're finished doing what you are doing", and then (which is the .then() part) I'll do something with the result

&nbsp;

* Are all callback functions considered to be Asynchronous? Why or Why Not?

Not all of them, because some callback functions need the result of something else, or the rest of the code needs the result of the callback, so not all functions can be asynchronous.
 


<br/><br/> 
<br/><br/> 



|401| [Home](https://suhaib-ersan.github.io/reading-notes/) |
|-|-|
| read00 | [Get Ready for 401](https://suhaib-ersan.github.io/reading-notes/401/read00) |
| read01 | [No de Ecosystem, TDD, CI/CD](https://suhaib-ersan.github.io/reading-notes/401/read01) |