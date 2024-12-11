# Tic-Tac-Toe-Python

Tic Tac Toe

![image](https://github.com/user-attachments/assets/01a053ae-52f8-4152-9e7a-85a313f177d0)


**About**

Tic Tac Toe is a simple game that is played by two players. The game is played on a 3x3 grid. The players take turns placing their symbol (either "X" or "O") in an empty cell. The first player to get three of their symbols in a row (horizontally, vertically, or diagonally) wins the game. If all cells are filled and no one has won, the game is tied.

**Requirements**

Python 3.x
Tkinter library (which is usually included with Python)
Getting Started
Clone this repository to your local machine.
Open a terminal window and navigate to the cloned repository.
Run the following command to start the game: python game.py
**How to Play**

The game is played on a 3x3 grid.
The players take turns placing their symbol (either "X" or "O") in an empty cell.
The first player to get three of their symbols in a row (horizontally, vertically, or diagonally) wins the game.
If all cells are filled and no one has won, the game is tied.
**Code Structure**

The code is organized into a single class, TicTacToe, which contains the following methods:
__init__(self, master) : This method initializes the game window, sets up the game board, and creates the buttons for the game board.

handle_click(self, row, col) : This method is called when a player clicks on a cell in the game board. It updates the game board and checks if the game is over (i.e. if a player has won or the game is tied).

switch_player(self) : This method alternates between "X" and "O" after each move.

check_win(self) : This method checks if any player has won the game by getting three of their symbols in a row.

check_tie(self) : This method checks if the game is tied (i.e. all cells are filled and no one has won).

game_over(self) : This method disables all buttons and displays a message announcing the winner or declaring a tie.


**Happy Learning enjoy!**
