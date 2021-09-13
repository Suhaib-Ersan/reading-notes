# AWS: Cloud Servers

* Describe the Web-Request-Response-Cycle

The web request response cycle starts with a request from a server, or maybe from a front end, or anything else, and that request is usually encrypted if it's under https, or even without it, sometimes developers encrypt any data you send though means like sending an encryption secret key some other way, so the other end can de-crypt that data.   
Afterwards, this data goes through different servers/the internet until it reaches the target destination, and then that target, which is a server, does whatever it wants with the data, usually including running that data through middleware, which are pieces of code that do some checks or do something with the data, and that's before any of the code in the access point is ran.   
after it reaches the access point code, the code runs and does it's thing, returning either an error or a success status code, with whatever data it wants to return.

&nbsp;

* Explain what a “server” is, as it relates to the WRRC

It's a program that can receive data through some access points, this allows it to be the backend of the request/response cycle.

&nbsp;

* What does it mean to “deploy” an application?

It means to move your application data from your local machine to a machine(server) that can accept connection from various sources, allowing your application to be used by users.



[Go back to table of contents](https://suhaib*ersan.github.io/reading*notes/) 