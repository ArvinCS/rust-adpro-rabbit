## Reflection

> What is amqp?

AMQP stands for Advanced Message Queuing Protocol. It's an open standard application layer protocol for message-oriented middleware. Essentially, it's a protocol used for exchanging messages between different systems or components in a way that is reliable, flexible, and interoperable.

> what it means? guest:guest@localhost:5672 , what is the first quest, and what is the second guest, and what is localhost:5672 is for?

It is a string for connection to an AMQP broker. Where each of them has a specific meaning:
1. First guest: This is the username used for authentication when connecting to the AMQP broker. In this case, the username is set to "guest". It's common for RabbitMQ, an AMQP broker, to have a default user named "guest" with the password "guest".
2. Second guest: This is the password used for authentication when connecting to the AMQP broker. In this case, the password is also set to "guest". It matches with the default password for the "guest" user in RabbitMQ.
3. localhost:5672: This part specifies the hostname and port of the AMQP broker. "localhost" refers to the local machine, meaning that the broker is expected to be running on the same machine where the Rust code is executed. "5672" is the default port number for AMQP connections.