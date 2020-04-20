# Puzzle-Solver

This program will solve both a sudoku and the 'Number Crunch' - a puzzle published by the newspaper known as 'The Australian'. Both of these puzzles are currently solved by brute force, however they do run within a 2 seconds. I may try to speed up the sudoku algorithm by looking for intuitive patterns similar to what humans look for - which will boost performance by minimizing the number of cells needed to fill in by trial-and-error. 

Any Version of Python2.7 or later should run this. You may need to pip install dependencies numpy, pandas, itertools, openpyxl to run this. 

Download solver.py and puzzle_template.xlsx into the same directory. Fill in the known quantities of either or both puzzles. For sudoku, this means fill in the numbers provided by the puzzle. For Number CRunch, this means fill out the numbers at the end of the rows and columns, as well as the operators (*, /, -, +). 

From that directory in terminal, run:
$ python solver.py

This will create a 'solved_puzzles.xlsx', where both solved puzzles will be produced. 
