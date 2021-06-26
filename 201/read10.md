# Error Handling & Debugging

## Execution Context & Hoisting

Each time a script enters a new execution context, there are two phases of activity:

#### 1: Prepare

• The new scope is created
• Variables, functions, and arguments are created
• The value of the this keyword is determined

#### 2: Execute

• Now it can assign values to variables
• Reference functions and run their code
• Execute statements

### Error Objects

There are seven types of built-in error objects in JavaScript:

| OBJECT | DESCRIPTION |
| Error | Generic error - the other errors are all based upon this error |
| Syntax Error | Syntax has not been followed |
| ReferenceError | Tried to reference a variable that is not declared/within scope |
| TypeError | An unexpected data type that cannot be coerced |
| Range Error | Numbers not in acceptable range |
| URI Error | encodeURI (), decodeURI(), and similar methods used incorrectly |
| EvalError | eval () function used incorrectly |


## How to Deal With Errors

If you come across an error while writing a script (or when someone reports a bug), you will need to debug the code, track down the source of the error, and fix it.
You will find that the developer tools available in every major modern browser will help you with this task.

Debugging is about deduction: eliminating potential causes of an error. You start with:

#### Where Is the Problem?

First, should try to can narrow down the area where the problem seems to be. In a long script, this is especially important.

1. Look at the error message, it tells you:

- The relevant script that caused the problem.
- The line number where it became a problem for the interpreter. (As you will see, the cause of the error may be earlier in a script; but this is the point at which the script could not continue.)
- The type of error (although the underlying cause of the error may be different).

2. Check how far the script is running. Use tools to write messages to the console to tell how far your script has executed.
3. Use breakpoints where things are going wrong. They let you pause execution and inspect the values that are stored in variables.

#### What Exactly Is the Problem?
Once you think that you might know the rough area in which your problem is located, you can then try to find the actual line of code that is causing the error.

1. When you have set breakpoints, you can see if the variables around them have the values you would expect them to. If not, look earlier in the script.

2. Break down I break out parts of the code to test smaller pieces of the functionality.
- Write values of variables into the console.
- Call functions from the console to check if they are returning what you would expect them to.
- Check if objects exist and have the methods / properties that you think they do.

3. Check the number of parameters for a function, or the number of items in an array.


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
| read09 | [Forms and JS Events](https://suhaib-ersan.github.io/reading-notes/201/read09) |
| **read10** | **Debugging** |
| read11 | [Audio, Video, Images](https://suhaib-ersan.github.io/reading-notes/201/read11) |
| read12 | [Docs for the HTML `<canvas>` Element & Chart.js](https://suhaib-ersan.github.io/reading-notes/201/read12) |
| read13 | [Local Storage](https://suhaib-ersan.github.io/reading-notes/201/read13) |
| read14 | [](https://suhaib-ersan.github.io/reading-notes/201/read14) |
| read15 | [](https://suhaib-ersan.github.io/reading-notes/201/read15) |