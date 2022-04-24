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

Example::
	
	onJoin() {
		broadcast("Hey! A person joined!");
	}
	
	
Send
~~~~
Sends a message to the specified player
``send(<string>, <player>)``

Example::
	
	onJoin() {
		send("Welcome back!", event.player);
	}
