# Express REST API

* Name 3 real world use cases where you’d want to change the request with custom middleware

Need to log every request that reaches the server and with what method.


&nbsp;

* True or false: The route handler is middleware?
true.


&nbsp;

* In what ways can a middleware function end the process and send data to the browser?
by doing a res.send(something).
or by next('message').


&nbsp;

* At what point in the request lifecycle can you “inject” middleware?
at the start, they're the first blocks of code from the developer (other than necessary server parts) that touch the code. 


&nbsp;

* What can cause express to error with “Request headers sent twice, cannot start a second response”
When the server mistakenly sends two responses, which gives you an error.



<br/><br/> 
<br/><br/> 



[Go back to table of contents](https://suhaib-ersan.github.io/reading-notes/) 