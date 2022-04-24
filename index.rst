index
├── Chat

Chat
====

Sending messages to chat
----

Broadcasting
~~~~
``broadcast(<string>)``
Sends a message to all players online however will not send a message to the console

Useage:
``broadcast(<message>)``

Example:
``
onJoin() {
  broadcast("Someone joined!");
}
``
