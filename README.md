# One player checkers using Minimax algorithm and PyGame
**Personal project**

The purpose of the project is to allow the user to play checkers against an opponent who follows the Minimax algorithm, by looking 5 moves ahead (or even more), optimized using Alpha-beta pruning. The player must select a legal move, which means that if possible, he must jump over the opponent's checker and eat it. To avoid infinite games, the result is a tie if there is no change in the number of checkers on the board and no checker manages to become a king for 50 consecutive moves. It is possible to look at the evaluation in real-time of the position by the algorithm in the bar below the board.

**Note:** game difficulty can be increased or decreased by adjusting the parameter of the function *minimax_fun* at line 222. By increasing the difficulty of the game, it's more difficult to win, but it also takes more time.


