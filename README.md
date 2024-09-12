# DS-GA-1007-Proj

A chess engine outputs the best move for a chess piece given a board position.

Backtracking its conclusion:

  * figuring out best move requires board state evaluation
    * With shorthand definition of board state
    * And color to move (same board has different evaluation for white to move and black to move)
  * figuring out board state evaluation requires looking at all possible moves from a given position
    * alpha-beta pruning, probably
    * how many levels down the tree?
    * time constraint?
  * if checkmate is found, go toward fastest checkmate
  * else:
    * still needs to calculate what constitutes a certain evaluation on a given board
