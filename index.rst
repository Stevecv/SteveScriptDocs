index
├── Chat
  ├── Broadcast

Chat
====

Sending messages to chat
----

Broadcast
~~~~
Send a message to all players online however will not send a message to the console
``broadcast(<string>)``

Useage:
``broadcast(<message>)``

Example::
  onJoin() {
    broadcast("Someone joined!");
  }
.. code-block:: rst
  onJoin() {
    broadcast("Someone joined!");
  }
