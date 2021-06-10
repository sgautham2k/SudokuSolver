# Sudoku Solver
A sudoku solver built using Python 3. I am going to warn you all, that this involves backtracking which is a pretty complex topic to get a grasp on if you are an absolute beginner/ rookie so I would advice looking at getting the grips of loops, functions and the basic instructions of python before you come to trying to understand this code. I'm currently working on building a GUI for it !

## Backtracking for Sudoku Solver
Such a program starts with a first possible action at a certain position. This position (and action) can be a random one, a first in the set of all actions and/or positions, or it can be an optimal “move” in a given situation. Program then continues with applying following actions at the following positions until all “moves” were taken and the problem has been solved.

If there is no further action available and the problem is still not solved, the applied action at the last position is backtracked (removed) and another, not yet tried action is applied.
