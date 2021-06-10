# Sudoku Solver - An Introduction

A sudoku solver built using Python 3. I am going to warn you all, that this involves backtracking which is a pretty complex topic to get a grasp on if you are an absolute beginner/ rookie so I would advice looking at getting the grips of loops, functions and the basic instructions of python before you come to trying to understand this code. I'm currently working on building a GUI for it !

# Backtracking for Sudoku Solver

Such a program starts with a first possible action at a certain position. This position (and action) can be a random one, a first in the set of all actions and/or positions, or it can be an optimal “move” in a given situation. Program then continues with applying following actions at the following positions until all “moves” were taken and the problem has been solved.

If there is no further action available and the problem is still not solved, the applied action at the last position is backtracked (removed) and another, not yet tried action is applied.

# GUI for Sudoku Solver

<img src="https://user-images.githubusercontent.com/70945303/121496774-d3a16780-c9eb-11eb-8610-ac3b18eeddf4.png" width="400" height="400">

## As you can see, we have the GUI for the sudoku solver which has a timer running to record the time taken to complete the sudoku puzzle.

<img src="https://user-images.githubusercontent.com/70945303/121497188-3abf1c00-c9ec-11eb-872a-befd73d8f7d3.png" width="400" height="400">

## The red highlighted box in the first grid show us trying to insert a number to check whether the number is valid in the respective position or not.

<img src="https://user-images.githubusercontent.com/70945303/121497546-9e494980-c9ec-11eb-8914-c0599467b356.png" width="400" height="400">

## As you can see, we tried to enter the number "2" which is already present in the first row of the sudoku puzzle. When we try to insert a number if it is present in the row or column, we get an "X" mark on bottom left of the board indicating that the number we inserted is not valid. 
