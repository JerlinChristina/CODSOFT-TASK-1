# CODSOFT-TASK-1
NAME:S.Jerlin Christina
COMPANY:Codsoft
DOMAIN:Artifical intelliegence
DURATION:January to February
This Python implementation of Tic-Tac-Toe allows a human player to play against an AI that is unbeatable, using the Minimax algorithm. The AI, playing as Player O, chooses the best move by evaluating all possible moves to maximize its chances of winning, while minimizing the human player's chances.
Key Concepts:
Minimax Algorithm:
The core idea behind Minimax is to simulate all possible game states (i.e., all possible moves for both players) and then evaluate each one to determine the optimal move for the AI.
The algorithm recursively evaluates each state to a terminal state (win, loss, or draw), and assigns a value:
1 for a win (AI wins),
-1 for a loss (Player X wins),
0 for a draw (no winner).
The AI will maximize its score (trying to win) and minimize the player's score (preventing the player from winning).
Alpha-Beta Pruning:
This optimization reduces the number of nodes evaluated by the Minimax algorithm.
By "pruning" (eliminating) branches that don't need to be explored (because they can't affect the final decision), it speeds up the process.
Game Flow:
The human player plays first as Player X and enters their move as a row and column index (from 0 to 2).
The AI, as Player O, then calculates the best move using the Minimax algorithm and makes its move.
The game ends when either the human player wins, the AI wins, or the game results in a draw.
Winning Conditions:
The game checks for winning conditions after each move (rows, columns, or diagonals).
It also checks if the board is full to declare a draw.
Features:
Unbeatable AI: Thanks to Minimax, the AI will always play optimally, ensuring that if it doesn't win, it will force a draw.
User Input: The human player provides their move by entering the row and column where they want to place their mark.
Real-Time Board Display: After every move, the current state of the board is printed, showing the updated game grid.
Conclusion:
This implementation provides a fun, interactive experience where the human player can try their best to outsmart an AI that uses game theory and search algorithms to always make the best decision. It serves as a great introduction to understanding Minimax, Alpha-Beta Pruning, and how to apply these concepts in AI game development
