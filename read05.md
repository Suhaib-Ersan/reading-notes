# Before scripting
HTML, CSS and JavaScript work together to make webpages come to life.
You start with HTML, this is the structure of your website. 
Then you add CSS to it, this styles the webpage, which is adding colors to things, adding backgrounds and similar.
Then you add JavaScript to the mix, this adds interactivity to the webpage.  
> _Keeping each one of them in a separate file is the better practice._

All of those languages can be written in plain text.
You can use JavaScript in two ways, first one is to add a `<script></script>` tag to HTML and code JavaScript inside it, the second way (and the better one) is to add a `<script src:"js-file.js">` to your HTML, allowing you to link to the jS file.
this means JavaScript won't change the sourcecode, it's just on top of it.
Usually, the best place to put the `<script>` tags is at the end of the `<body>` tag in the HTML file.

# Scripting
A script is a series of instructions that a computer can follow. Each individual instruction is known as a statement, and those end with a semicolon `;`.
> _Dont forget, JavaScript is case sensitive_

You can group any number of statements together by using what's called a **code block**, which are statements inside curly brackets `{}`.
There's also something called variables, which are identification names or numbers, so you the computer (and you) can know what data are you talking about. As the name suggests, these can be changed at will.
Making variables is easy, you just have to write `var` and then write the name of the variable, followed by a semicolon (or other code).
It should look like something like this: `var visiter_age;`.
Giving the variable a value is also easy, just use the equal `=` sign, it should look like something like this: `visiter_age = 25`, and now the visiter_age is 25.
There are a few rules for naming variables, like:
* The name must begin with a letter, dollar sign ($),or an underscore (_). It can't start with a number. 
* The name can contain letters, numbers, dollar sign ($), or an 
underscore (_). Note that you must not use a dash(-) or a period (.) in a variable name. 
* You cannot use keywords or reserved words, which are words that already have a purpose in JS. 
## Data Types
There are three main data types in JS:
* Numeric
which are just numbers, like: `200` or `0.15` or `-900` or `50000`.
* String 
Which is a data type consisting of letters and other similar characters, like: `hello` or `Adam` or `!!!`.
* Boolean
This data type only has two states: true or false, and is used to know the results of code and act on them.


<br></br>
<br></br>

| [Home](https://suhaib-ersan.github.io/reading-notes/) | [read01](https://suhaib-ersan.github.io/reading-notes/read01) | [read02](https://suhaib-ersan.github.io/reading-notes/read02) | [read03](https://suhaib-ersan.github.io/reading-notes/read03) | [read04](https://suhaib-ersan.github.io/reading-notes/read04) | **read05** | [read06](https://suhaib-ersan.github.io/reading-notes/read06) |
|-|-|-|-|-|-|-|