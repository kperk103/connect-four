# battleship

some reference links:
- minimax algorithm: https://www.geeksforgeeks.org/minimax-algorithm-in-game-theory-set-1-introduction/
- battleship minimax reference code: https://github.com/topics/battleship-game?l=c%23
- gpt design: in google docs
- import random

- - game: 2 separate boards - 10x10 array which labels indices as either empty, taken or not by a ship (0 or 1 or 2 or 3), tostring method, number of ships being placed
- player: my current number of ships that have been hit (if it is equal to 5, return that the player has lost), a function saying whether the player has lost or won, a set of guessees i have already made, and user facing stuff
- ship: need to know if its been hit and its size (Once the guessing begins, the players may not move the ships. The 5 ships are: Carrier (occupies 5 spaces), Battleship (4), Cruiser (3), Submarine (3), and Destroyer (2)), check the starting coordinates and then vertical and horizontal - add if successful, reject if not successful

- what is the improvement in performance when minimax is provided with imperfect information about the game state?
