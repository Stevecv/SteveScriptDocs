index
├── Chat

Chat
====

Sending messages to chat
----

Broadcasting
~~~~
Send a message to all players online however will not send a message to the console
``broadcast(<string>)``

Useage:
``broadcast(<message>)``

Example:
.. code-block:: rst
  onJoin() {
    broadcast("Someone joined!");
  }
