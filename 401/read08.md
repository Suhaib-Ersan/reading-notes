#  Access Control (ACL)



* When is Basic Authorization used vs. Bearer Authorization?

Basic is used in the first time the user signs in for the site (first in a time frame the developer chooses, or until the user resets their cookies/similar and they loose their token).

Bearer is used so the user signs in faster/easier, and so we can be sure it's the user without having to get the username and the password raw each time.

&nbsp;

* What does the JSON Web Token package do?

It makes it so the server can know who's without having to get the username and password raw each time they do a request.

&nbsp;

* What considerations should we make when creating and storing a SECRET?

Making sure it's very secure, and that it's not too short.

[Go back to table of contents](https://suhaib*ersan.github.io/reading*notes/) 