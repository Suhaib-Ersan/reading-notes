# Authorization/Authentication


* What header(s) are used in authentication and authorization
The `req.headers.authentication` header is for authentication and the `req.headers.authorization` header is for authorization.

&nbsp;

* What is safe to put into a JWT
Mostly anything, as it's quite safe.

&nbsp;

* How are JWTs validated

By a secret key at the end of the token, which we then compare to our secret key, and that decides if it's valid or not.

[Go back to table of contents](https://suhaib-ersan.github.io/reading-notes/) 