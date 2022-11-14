# sudokuSolver
The code divides the whole 9x9 sudoku board into 9 rows and as it satisfies the values in empty spaces it simultanously keeps checking the validity of that number with 
respect to the rest of the board.

The sudokuSolver is based upon backtracking algorithm.

Backtracking - trys to build a solution incrementally and recursively. If a value entered violates the base set rules, then it backtracks and checks for another value
			untill answer is found
