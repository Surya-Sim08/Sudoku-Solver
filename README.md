# Sudoku-Solver

### Sudoku Solver in Python language.
This project is a basic Sudoku Solver implemented in Python. It uses a backtracking algorithm to fill in the missing numbers in a 9x9 Sudoku grid. The script is simple yet effective for solving standard Sudoku puzzles.

### Features
Solves a 9x9 Sudoku grid with partially filled cells.
Uses a recursive backtracking algorithm to explore all possible solutions.
Validates numbers for rows, columns, and 3x3 sub-grids before placing them.

### How It Works
1. The grid variable is initialized with a partially filled Sudoku puzzle. Empty cells are represented as 0.
2. The possible() function checks if placing a number in a specific cell is valid:
Ensures the number does not already exist in the same row.
Ensures the number does not already exist in the same column.
Ensures the number does not already exist in the same 3x3 sub-grid
3. The solve() function:
Recursively tries all possible numbers for each empty cell.
Backtracks if no valid number can be placed.
4. The solved grid is displayed once a valid solution is found.

### How to Use
Install Python 3.x and the numpy library:
pip install numpy

Copy the code into a Python file, e.g., sudoku_solver.py.

Run the script:
python sudoku_solver.py

View the solved Sudoku grid in the console.

### Notes
The script works with standard 9x9 Sudoku puzzles.
If multiple solutions exist, the script may display only one at a time. Press Enter to explore further solutions.
Modify the grid variable to test different Sudoku puzzles.
