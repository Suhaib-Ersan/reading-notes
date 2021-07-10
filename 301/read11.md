# Authentication



* What is OAuth?

OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential


&nbsp;


* Give an example of what using OAuth would look like.

when you go to log onto a website and it offers one or more opportunities to log on using another website’s/service’s logon

&nbsp;


* How does OAuth work? What are the steps that it takes to authenticate the user?

When you try to login to a site using OAuth, this site connects to another website(that uses OAuth) you already logged in to, and then a token is generated between the two so you can log in,.

&nbsp;


* What is OpenID?

It's an alternative to OAuth, but it tries to actually identify users and make sure the access is secure, while OAuth is more about authorizing more than authenticating.

&nbsp;



## Authorization and Authentication flows

* What is the difference between authorization and authentication?

Authorization is only giving access to simple, or general info about your account, and not really giving away any private info.
While Authentication tries to actually authenticate who the user is, and make sure who ever is logging in is actually the owner of the account.

&nbsp;


* What is Authorization Code Flow?

It exchanges an Authorization Code for a token so the user can login to website using credentials from another.

&nbsp;


* What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

When public clients (e.g., native and single-page applications) request Access Tokens, some additional security concerns are posed that are not mitigated by the Authorization Code Flow alone.
So,OAuth 2.0 provides a version of the Authorization Code Flow which makes use of a Proof Key for Code Exchange (PKCE)

&nbsp;


* What is Implicit Flow with Form Post?

Implicit Flow with Form Post flow uses OIDC to implement web sign-in that is very similar to the way SAML and WS-Federation operates. The web app requests and obtains tokens through the front channel, without the need for secrets or extra backend calls. With this method, you don’t need to obtain, maintain, use, and protect a secret in your application.

&nbsp;


* What is Client Credentials Flow?

M2M (machine-to-machine) apps use the Client Credentials Flow in which they pass along their Client ID and Client Secret to authenticate themselves and get a token.

&nbsp;


* What is Device Authorization Flow?

With input-constrained devices that connect to the internet, rather than authenticate the user directly, the device asks the user to go to a link on their computer or smartphone and authorize the device. This avoids a poor user experience for devices that do not have an easy way to enter text.

&nbsp;


* What is Resource Owner Password Flow?

highly-trusted applications can use the Resource Owner Password Flow, which requests that users provide credentials (username and password), typically using an interactive form. The Resource Owner Password Flow should only be used when redirect-based flows (like the Authorization Code Flow) cannot be used.



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
| read10 | [In memory storage](https://suhaib-ersan.github.io/reading-notes/301/read10) |
| read11 | **Authentication** |
| read12 | [Mongo and Mongoose](https://suhaib-ersan.github.io/reading-notes/301/read12) |
| read13 | [CRUD](https://suhaib-ersan.github.io/reading-notes/301/read13) |
| read14 | [Project Ideas](https://suhaib-ersan.github.io/reading-notes/301/read14) |
| read15 | [Project Kickoff](https://suhaib-ersan.github.io/reading-notes/301/read15) |