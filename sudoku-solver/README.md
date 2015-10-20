# Sudoku Solver

## Problem Statement

__The task in this challenge is:__

__Build a simple Sudoku solver for the standard 9 by 9 grid.__

The user inputs a board position thus:

((5,3,b),(b,7,b),(b,b,b)),((6,b,b),(1,9,5),(b,b,b)),((b,9,8),(b,b,b),(b,6,b)),((8,b,b),(b,6,b),(b,b,3)),((4,b,b),(8,b,3),(b,b,1)),((7,b,b),(b,2,b),(b,b,6)),((b,6,b),(b,b,b),(2,8,b)),((b,b,b),(4,1,9),(b,b,5)),((b,b,b),(b,8,b),(b,7,9))

(This corresponds to the Sudoku board shown in the Wikipedia link; the b's stand for blank spaces.)

The output should be:

Case 1: If the board is solvable and has a unique solution
Output: The solution to the puzzle is (output board position similar to the input board position) The solved Sudoku board if the puzzle is solvable. Output format should be similar to the input format.

Case 2: The board has no solutions. Output should be "Board has no solutions."

Case 3: The board has multiple solutions. You can choose to output a board position if you want.