# py_sudoku

## Sudoku

Basic Sudoku game I built in `python`, runs in the console (No GUI).

----------------------------------------------------
## Index

- Rules
- Game Features
- Controls
- Installation
- License

----------------------------------------------------
## Rules

The objective is to fill the 9×9 grid with digits so that each column, each row, and each of the nine 3×3 subgrids that compose the grid contain all of the digits from 1 to 9.

When placing a new digits you have to make sure it doesn't already exits on the same row, column or box in order to win.


Press Submit(S) to check if your answers are correct.

----------------------------------------------------
## Game Features

- 3 different difficulties
  - Easy
  - Medium
  - Hard
- A variety of boards to play from
- Randomize and Clear

----------------------------------------------------
## Controls

|                       | TEXT                        |
|-----------------------|-----------------------------|
| Choose Difficulty     | Type <kbd>E, M or H</kbd>   |
| Enter Box Coordinates | Type <kbd>LetterDigit</kbd> |
| Choose box            | <kbd>left click</kbd>       |
| Enter Number          | <kbd>1-9</kbd>              |
| Quit            	    | Type <kbd>Q</kbd> 		  |
| Submit			    | Type <kbd>S</kbd>	   	   	  |
|-----------------------|-----------------------------|

----------------------------------------------------
## Installation

INSTALLATION INSTRUCTIONS:

For MacOS/Linux:

In terminal install python3 (if not already installed) using:

	$ brew install python3

Next, install some other packages using:

	$ sudo easy_install pip
	$ sudo pip3 install Pillow
	$ pip install pyinstaller

Now clone our repo onto your computer:

	$ git clone https://github.com/290squadsix/squad_six_repo.git

Enter the repo directory:

	$ cd squad_six_repo

You are done! To run the game, simply type the following:

	$ python3 sudoku_gui.py


