# python-Project
My project is about  a Tic Tac Toe game implemented using the Tkinter library in Python. The game allows two players to take turns placing their respective symbols (X' or '0) on the board until one of them wins or the game ends in a draw.
Here's a brief explanation of the code:

Importing necessary modules:

from tkinter import *: Imports the tkinter module, which is used for creating the GUI.
import tkinter.messagebox: Imports the messagebox module from tkinter for displaying messages.
Initializing the Tkinter application:

root = Tk(): Creates the main window for the game.
Setting up the GUI components:

Tops, MainFrame, LeftFrame, and RightFrame are frames used to organize the layout of the GUI.
Button widgets are used to create the Tic Tac Toe board.
Label widgets are used to display messages, player names, and scores.
Entry widgets are used to input player names.
The checker function:

This function is called when a player clicks on a button on the Tic Tac Toe board.
It checks if the clicked button is empty (' ') and then fills it with the current player's symbol ('X' or 'O') and updates the button's appearance accordingly.
The scorekeeper function is then called to check if the game is won by any player.
The scorekeeper function:

This function checks if any player has won the game after each move by checking all possible winning combinations.
If a player wins, it updates their score, displays a message box announcing the winner, and calls the reset function to prepare for the next game.
The reset function:

This function resets the Tic Tac Toe board and clears the scores.
The Newgame function:

This function resets the game, clears the player names, and sets the scores to zero when the "New Game" button is clicked.
Running the Tkinter main loop:

root.mainloop(): This method starts the Tkinter event loop and keeps the GUI application running until the user closes the window.
Overall, the code defines the GUI elements and provides logic to play a game of Tic Tac Toe between two players. When a player wins, a message box pops up to announce the winner, and players' scores are updated accordingly. The "Reset" button clears the board, and the "New Game" button resets the game entirely.
