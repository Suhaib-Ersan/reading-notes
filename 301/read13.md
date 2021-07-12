# CRUD

## Reading 

* In your own words, describe what each group of status code represents:
  * 100’s = for information only, like if the server can't accommodate what the client is asking.
  * 200’s = success codes, tells the client the request was accepted.
  * 300’s = these tell the client that the information they want is no longer available there, and redirects them.
  * 400’s = error codes.
  * 500’s = error codes, but for the server.



&nbsp;


* What is a status code 202?

the request met all validation requirements at the time of sending

&nbsp;


* What is a status code 308?

 This tells the client to use another URL to access the resource and not use the current URL anymore.

&nbsp;


* What code would you use if an update didn’t return data to a client?

204 

&nbsp;


* What code would you use if a resource used to exist but no longer does?

410 

&nbsp;


* What is the ‘Forbidden’ status code?

The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.


&nbsp;

## Videos

Why do we need to pull our MongoDB database string out of our server and put it into our .env?

because you won't use the localhost when it's on another computer/server.

&nbsp;


* What is middleware?

it's code that runs after a request was passed, but before it gets to the route.

&nbsp;


* What does `app.use(express.json())` do?

this lets the server accept json as a body

&nbsp;


* What does the `/:id` mean in a route?

a parameter the client passes to the sever, you can access it through `request.params.id ` which allows you to access whatever they pass after that `/`.

&nbsp;


* What is the difference between `PUT` and `PATCH`?

put updates the whole object, patch only updates whatever gets passed from the client.

&nbsp;


* How do you make a default value in a schema?

 by writing `default` inside a schema and then using the value/function you want as a value

&nbsp;


* What does a `500` error status code mean?

the server had an internal error

&nbsp;


* What is the difference between a status `200` and a status `201`?

200 means the request was successful, but 201 says the create request was successful.


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
| read10 | [In memory storage](https://suhaib-ersan.github.io/reading-notes/301/read10) |
| read11 | [Authentication](https://suhaib-ersan.github.io/reading-notes/301/read11) |
| read12 | [Mongo and Mongoose](https://suhaib-ersan.github.io/reading-notes/301/read12) |
| read13 | **CRUD** |
| read14 | [Project Ideas](https://suhaib-ersan.github.io/reading-notes/301/read14) |
| read15 | [Project Kickoff](https://suhaib-ersan.github.io/reading-notes/301/read15) |