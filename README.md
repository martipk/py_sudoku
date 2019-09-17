# py_sudoku

----------------------------------------------------

## Sudoku

Basic Sudoku game built in `python`, runs in the console (No GUI).

## Index

- Rules
- Game Features
- Controls
- Installation
- License

## Rules

The objective is to fill the 9×9 grid with digits so that each column, each row, and each of the nine 3×3 subgrids that compose the grid contain all of the digits from 1 to 9.

When placing a new digits you have to make sure it doesn't already exits on the same row, column or box in order to win.

Press Submit(S) to check if your answers are correct.

## Game Features

- 3 playable difficulties, depending on amount of spaces to fill:
  - Easy: 20
  - Medium: 35
  - Hard: 50

- Over 1 million randomly generated unique boards and countless generated puzzles.

## Generating 362'880 Sudoku Boards from One Input

No this is not clickbait, the function `get_random_puzzle()` in `puzzles.py` can generate 362'880 unique sudoku boards from just one inputted board.
If you look at a completed sudoku board you will notice that if you replace all the "1"s with "2"s, and all the previous "2"s with "1"s the board is still valid. Using this idea, I will pick a random digit that I will use for all "1"s in the board. Next I will pick a second random digit, that is not equal to the first for all "2"s... Doing this for all 9 digits will completely randomize your grid.
Notice `9! = 362'880`. If you do not want the pattern to be noticeable, you can add other boards that have the number locations differently. This is why there are 3 unique with unique locations, boards. So `3 * 9! = 1'088'640`.


## Controls

| ACTION                | COMMAND         |
|-----------------------|-----------------|
| Choose Difficulty     | <kbd>E</kbd>, <kbd>M</kbd> or <kbd>H</kbd>|
| Enter Box Coordinates | (LetterDigit) eg. <kbd>A4</kbd>|
| Enter Number          | <kbd>1-9</kbd>|
| Quit            	    | <kbd>Q</kbd>|
| Submit			    | <kbd>S</kbd>|

## Installation

For MacOS/Linux:

In terminal install python3 (if not already installed) using:

	$ brew install python3

Next, install some other packages using:

	$ sudo easy_install pip
	$ sudo pip3 install Pillow
	$ pip install pyinstaller

Now clone our repo onto your computer:

	$ git clone https://github.com/martipk/py_sudoku.git

Enter the repo directory:

	$ cd py_sudoku

You are done! To run the game, simply type the following:

	$ python3 sudoku_console.py


