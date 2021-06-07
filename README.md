# cardgame1
The game company, Silly Little Games, has come up with a new card game for you to simulate. It uses a special set of cards that contain the numbers 1 to 13 and there are four copies of each card in the deck (if you want to try out this game with a regular card deck, you can make Ace = 1, Jack = 11, Queen = 12, King = 13). The first person to play all the cards in their hand wins.

The game is played as follows:

The cards are shuffled and placed into a stack
Each player is dealt 7 cards from the stack in a round-robin fashion and their cards are placed into their queue
The next card in the deal stack is placed into the discard stack
For their turn, each player plays the next card in his/her queue. 
If the card the player plays is HIGHER in number than the one on the top of the discard stack, the player's turn is over.
If the card the player plays is EQUAL in number to the one on the top of the discard stack, the player must then take one card from the deal stack and the player's turn is over.
If the player's card is LOWER in number than the one on the discard stack, the player must take two cards from the deal stack and the player's turn is over.
If the deal stack runs out of cards, "turn over" the discard stack and continue the game.
Note that you must keep the same card on the top of the discard stack, so you will need to hold onto that card and push it back onto the discard stack before continuing the game.
The first player to run out of cards wins the game.
Offer to repeat the game as many times as desired.
Notes:

There are only two players.
You may ask for names or simply call them by whatever names your game chooses.
You must use a stack for the shuffled cards, a stack for the discard pile and a queue for each player - all of type int.
