# py_sudoku

## Sudoku

Basic Sudoku game built in `python`, runs in the console (No GUI).

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

- 3 playable difficulties, depending on amount of spaces to fill:
  - Easy: 20
  - Medium: 35
  - Hard: 50

- Up to 1 million randomly generated boards and countless generated puzzles.

----------------------------------------------------
## Controls

| ACTION                | COMMAND         |
|-----------------------|-----------------|
| Choose Difficulty     | <kbd>E</kbd>, <kbd>M</kbd> or <kbd>H</kbd>|
| Enter Box Coordinates | (LetterDigit) eg. <kbd>A4</kbd>|
| Enter Number          | <kbd>1-9</kbd>|
| Quit            	    | <kbd>Q</kbd>|
| Submit			    | <kbd>S</kbd>|

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


