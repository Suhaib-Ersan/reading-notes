# Message Queues

* What does it mean that web sockets are bidirectional? Why is this useful?

It means the sockets can receive and send data, that is helpful when you are trying to make a system that needs to send data as also as receive it.

&nbsp;

* Does socket.io use HTTP? Why?

Only at the first request, afterwards no, because HTTP takes too much time and effort for it to be used for realtime apps.

&nbsp;

* What happens when a client emits an event?

It gets sent to the specified socket.

&nbsp;

* What happens when a server emits an event?

It gets sent to the specified socket.


&nbsp;

* What happens if a client “misses” an event?

Depends if it's using TCP or UDP, if it's using TCP then that gets sorted out between the client and the server until it's received or it times out.
In UDP the operation just keeps going since UDP doesn't check with the client for missed events.

&nbsp;

* How can we mitigate this?

By writing code that takes into account probably exceptions.

[Go back to table of contents](https://suhaib*ersan.github.io/reading*notes/) 