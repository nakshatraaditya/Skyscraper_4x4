# Skyscraper_4x4

**Task : 4x4 Grid Puzzle Solver**

This project implements a Python solution for the task. It involves solving a 4x4 skyscraper puzzle, where each cell in the grid represents a tower with a height from 1 to 4. The objective is to fill the grid such that each row and column contains each number exactly once, while satisfying visibility clues provided for the top, bottom, left, and right of the grid. These clues indicate how many towers are visible from each direction, with taller towers blocking shorter ones.

The implementation uses a constraint propagation approach, representing each cell as a set of possible values and iteratively applying rules to reduce possibilities until the grid is solved. The code includes functions to:
- Initialize the grid and clues.
- Apply logical constraints based on uniqueness, clue values, pairs, and item existence.
- Solve four specific puzzle configurations provided in the task.

The solver is built using Python 3 and NumPy. It outputs the solving process and the final grid configuration if a solution is found.

