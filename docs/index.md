Azure Queue Storage
Queues have been around for a long time — their simple FIFO (first in, first out) architecture makes queues a versatile solution for storing messages that do not need to be in a certain order. In simple terms, Azure Queue Storage is a service that allows users to store high volumes of messages, process them asynchronously and consume them when needed while keeping costs down by leveraging a pay-per-use pricing model.

Azure Storage Queues Components
Queue storage is composed of the following elements:

Storage Account, which contains all your storage services.

Queue, composed of a set of messages.

Message, includes any kind of information. For example, a message could be a text message that is supposed to trigger an event on an app, or information about an event that has happened on a website. A message, in any format, can only be up to 64KB in size and the maximum time that a message can remain in a queue is seven days.

However, a single queue can hold up to 200TB worth of messages. Messages can be text strings or arrays of bytes containing any kind of information in formats such as XML, CSV, etc.
