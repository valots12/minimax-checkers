# One player checkers using Minimax algorithm and PyGame
**Personal project**

The porpose of the project is to allow the user to play checkers against an opponent that follows the Minimax algorithm, looking 5 move ahead (or even more). The player must choose a legal move, meaning that if is possible he must jump over an opponent's checkers and eat it. To avoid infinite games, the result is a tie if there is no change in the number of checkers on the board and no checker manages to became a king. It is possible to look at the evaluation in real time of the position by the algorithm in the bar below the board.

**Note:** the difficulty of the game can be increased or decraesed by changing the parameter of the function *minimax_fun* at line 222. Increasing the difficulty of the game make it more difficult to win but requires also more time.


