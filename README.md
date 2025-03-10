# Tic-Tac-Toe-Solver_202401100400073
Game Setup:

The game is played on a 3x3 grid, initially empty.
Two players: One player uses 'X' and the other uses 'O'.
Objective:

The goal is to get three of your marks (either 'X' or 'O') in a row, column, or diagonal.
Game Flow:

Players take turns to place their marks in any empty cell on the grid.
Player 1 typically uses 'X' and Player 2 uses 'O'.
The AI plays as 'O', and the human player plays as 'X'.
Winning Conditions:

A player wins if they manage to place three of their marks in a row, column, or diagonal.
Draw Condition:

If all cells are filled and no player has won, the game results in a draw.
Game Termination:

The game ends when:
A player wins (three marks in a row, column, or diagonal).
The board is full, and no one wins (resulting in a draw).
AI in Tic-Tac-Toe:

The AI (playing 'O') makes decisions based on the Minimax algorithm.
Minimax evaluates all possible moves, aiming to maximize the AI's chance of winning and minimize the human player's chances.
Minimax Algorithm:

The AI evaluates every possible future game state by simulating all possible moves.
The algorithm "maximizes" for the AI’s turn and "minimizes" for the human player's turn, recursively.
Each possible move is assigned a score based on its desirability (win, loss, or draw).
Human Player's Role:

The human player (playing 'X') tries to outsmart the AI by either:
Getting three 'X's in a row, or
Blocking the AI from winning.
Endgame:

The game concludes when either a player wins or when the grid is completely filled with no winner, which results in a draw.
