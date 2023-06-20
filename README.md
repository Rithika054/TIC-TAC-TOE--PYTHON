#TIC TAC TOE
 Our objective is to build a two-player Tic Tac Toe game where players can take turns marking 'X' or 'O' on a 3x3 grid.
The first player to get three of their marks in a row (horizontally, vertically, or diagonally) wins the game.
We'll be using Python to implement the game logic and provide a user-friendly interface.
Let's understand the flow of the game:
Display the empty game board.
Take input from Player 1 to place 'X' on the board.
Display the updated board.
Check if Player 1 has won. If yes, end the game.
Take input from Player 2 to place 'O' on the board.
Display the updated board.
Check if Player 2 has won. If yes, end the game.
Repeat steps 2-7 until a player wins or the game ends in a draw.
Set up the game board:

Create a 3x3 grid to represent the Tic Tac Toe board.
Use a list of lists or a nested list to store the board state.
Display the game board:

Write a function to print the current state of the board.
Use loops to iterate over the nested list and print the grid.
Get input from players:

Write a function to prompt the current player for their move.
Accept the row and column numbers where the player wants to place their mark.
Update the game board:

After receiving valid input from the player, update the board state with the corresponding mark ('X' or 'O').
Check for a winner:

Write a function to check if the current player has won the game.
Check all possible winning combinations: rows, columns, and diagonals.
Main game loop:

Combine the above steps in a loop that continues until a player wins or the game ends in a draw.
