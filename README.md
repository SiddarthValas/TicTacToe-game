

#Tic-Tac-Toe Game


This is a simple command-line Tic-Tac-Toe game built using Python. The project demonstrates basic game logic, user interaction, and an implementation of a two-player game in the terminal.

Table of Contents

	•	Features
	•	Requirements
	•	Installation
	•	Usage
	•	Game Rules
	•	Code Structure
	•	Future Enhancements

Features

	•	Two-player mode
	•	Interactive command-line interface
	•	Input validation for a smooth user experience
	•	Basic error handling

Requirements

	•	Python 3.x

Installation

	1.	Clone the repository:

git clone https://github.com/SiddarthValas/tictactoe-python.git


	2.	Navigate to the project directory:

cd tictactoe-python


	3.	Run the game:

python tictactoe.py


Usage

	1.	The game will prompt Player 1 to enter their position, followed by Player 2.
	2.	Enter your move by selecting a position from 1 to 9 that corresponds to a cell in the Tic-Tac-Toe grid.
	3.	The game will display the board after each move and notify the players of the outcome (win, draw, or next turn).

Game Rules

	•	The game board is a 3x3 grid with positions numbered as follows:

1 | 2 | 3
---------
4 | 5 | 6
---------
7 | 8 | 9


	•	Player 1 is assigned ‘X’ and Player 2 is assigned ‘O’.
	•	Players alternate turns, choosing an empty position on the board.
	•	The first player to align three symbols (horizontal, vertical, or diagonal) wins.
	•	If all nine positions are filled without a winner, the game ends in a draw.

Code Structure

	•	tictactoe.py: Contains the game logic, including functions to display the board, validate moves, check for win conditions, and manage game flow.

Future Enhancements

	•	Add a GUI version of the game using libraries like Tkinter or Pygame.
	•	Implement a single-player mode with an AI opponent.
	•	Improve input validation and error handling for a more robust user experience.


Siddarth Valasubramanian

Enjoy the game!
