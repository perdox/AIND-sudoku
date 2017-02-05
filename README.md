# Artificial Intelligence Nanodegree
## Introductory Project: Diagonal Sudoku Solver

# Question 1 (Naked Twins)
Q: How do we use constraint propagation to solve the naked twins problem?  
A: The variables (possible digits for peers) are reduced by elimating digits from the set of possible box values that are out of question due to the fact that a set of two boxes shares a pair of possible digits, therefore rendering those digits impossible as values for their peers. This reduction of variables is constraint propagation. 

# Question 2 (Diagonal Sudoku)
Q: How do we use constraint propagation to solve the diagonal sudoku problem?  
A: By adding the two diagonals as units to the unitlist additional constraints are enforced reducing variables while solving the puzzle. 

### Install

This project requires **Python 3**.

### Code

* `solutions.py` - Main code for sudoku solver using only choice, elimnation, naked twins and search algorithms.
* `solution_test.py` - Do not modify this. You can test the solution by running `python solution_test.py`.
* `PySudoku.py` - Do not modify this. This is code for visualizing the solution.
* `visualize.py` - Do not modify this. This is code for visualizing the solution.

### Visualization

![Visualization](https://github.com/perdox/AIND-sudoku/raw/master/images/visualization.gif)

### Data

The data consists of a text file of diagonal sudokus.