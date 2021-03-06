
## Games developed with Python

## Table of contents

- [Snake](#snake)
- [Sudoku](#sudoku)

# Snake

Snake game developed with **tkinter**. When the player press `Start Game` button, the game begins,
and he must guide a tiny snake to get the purple rectangles. Every time the snake gets the
purple rectangle, it grows an extra block. If the snake bumps into the blue edge on the screen
or accidentally eats itself the game is over. The more purple blocks the snake eats the higher
the score.

![Snake_Start Window](img/snake.png)

# Sudoku

This game was developed with **tkinter**. The game arranges numbers in 9 by 9 matrix. The rules
are as follows:

- The number in each row and column should by between 1 and 9 and should appear only once.
- The 9x9 matrix is made of nine 3x3 matrices. The number in each of this matrices should
  also be between 1 and 9 and should appear only once.

This version includes an intuitive interface with the ability to check for errors and to show
solution. The most important component in this game is the SudokuLogic class, where the backtracking
algorithm was implemented. We use backtracking to generate random sudoku puzzles and to find the solution.

![Sudoku_Start Window](img/sudoku.png)
