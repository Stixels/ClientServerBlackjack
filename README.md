# ClientServerBlackjack
## Project Description

The project includes three files: the multithreaded server, the deck, and the clientGUI.

## Server
The server must be run in order to accept connections from clients. It will print out its address, and create a deck for the new clients. This is basically all the interaction the server needs to work.  (With the exception of restarting the server when you run out of cards in a deck.)

## Deck
A deck is created automatically when you run the server. Holds the string values for every card on the deck.

## clientGUI
When you run the clientGUI it will ask you for the address in the terminal. After that it will connect to the server and start the game GUI. (there will be no more need to interact with the terminal.)

It will pop up a box where you can insert your name and the game will greet you. Then, you can hit the start button and play the game normally. Hit will receive a new card. Stand will send your current hand value to the server to check. You can also press the quit button at any time or when the server runs out of cards.
