# AWS: Events


* Describe the similarities between AWS API Gateway + Lambda functions and an ExpressJS Server

They are similar in that they actually do a very similar thing, if not the same.

&nbsp;

* List the AWS Database offerings and talk about the pros and cons of each

They are many, like Amazon Aurora database, which is a MySQL and PostgreSQL-compatible relational database, which gives it the strengths and weaknesses of SQL databases.
Also Amazon DynamoDB, which is a key-value noSQL database, again, which gives it the strengths and weaknesses of SQL databases.

&nbsp;

* What’s the difference between a FIFO and a standard queue?

"Standard queues provide at-least-once delivery, which means that each message is delivered at least once.

FIFO queues provide exactly-once processing, which means that each message is delivered once and remains available until a consumer processes it and deletes it. Duplicates are not introduced into the queue."

From amazons website.

&nbsp;

* How can the server be assured a message was properly received?

By waiting for a packet from the client that tells the server that the message was actually delivered.


[Go back to table of contents](https://suhaib*ersan.github.io/reading*notes/) 