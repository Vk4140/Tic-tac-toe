# Tic-tac-toe

This is a Python implementation of the classic Tic Tac Toe game, where two players take turns marking spaces in a 3x3 grid. The first player to get three of their marks in a row wins the game.

Getting Started
To run this game, you'll need to have Python 3 installed on your computer. Then, download or clone this repository to your local machine.

How to Play
To start the game, run the tictactoe_game.py file in a Python environment. The game will ask for the names of the two players, and then display the game board:



   |   |   
___|___|___
   |   |   
___|___|___
   |   |   
   |   |   


Player 1 will be assigned the marker 'X', and Player 2 will be assigned the marker 'O'. The game will prompt the current player to choose a space on the board to mark, by entering a number from 1 to 9:


Player 1 (X), choose your move (1-9):
The game will continue until one player wins by getting three of their markers in a row, or until the game ends in a tie.

Game Features
Game Board
The game board is displayed in the console, and is a 3x3 grid of spaces. Each space is numbered from 1 to 9, as shown below:


1 | 2 | 3  
--|---|--
4 | 5 | 6  
--|---|--
7 | 8 | 9
Scoreboard
After each game, the scoreboard will be displayed showing the number of wins for each player:


--------------------------------
         The SCOREBOARD for TIC TAC TOE PYTHON GAME
--------------------------------
    Player 1      2
    Player 2      1
--------------------------------
Validating User Input
The game will validate user input to ensure that:

The chosen move is a number from 1 to 9
The chosen space is not already occupied by a marker


Handling Exceptions
The game will handle exceptions and display error messages for invalid input:

If the user enters a non-numeric value when choosing a move
If the user enters a number outside the range of 1 to 9 when choosing a move

Authors
----Your Name


Acknowledgments
This game was created as a fun programming exercise in Python, and was inspired by the classic Tic Tac Toe game.
