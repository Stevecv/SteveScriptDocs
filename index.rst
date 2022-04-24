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

A cool bit of code::
onJoin() {
  broadcast("Someone joined!");
}
.. code-block:: rst

