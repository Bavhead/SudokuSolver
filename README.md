# SudokuSolver
Multi-algorithmic sudoku solver and generator.

Supports the following algorithms or any combination:
- Brute Force (default)
- Forward Checking (FC)
- Arc Consistency
- Norvig (NOR)
- Minimum Remaining Value w/o Tiebreaker (MRV)
- Minimum Remaining Value w/Tiebreaker (MAD)
- Least Constraining Value (LCV)

## Installation
Ensure [Python](https://www.python.org/downloads/) (version 3.8 and greater) is installed.

Simply clone the repository to the intended location.

## Usage
To run, call
```
python3 src/Main.py <path_to_board_text_file_if_any> <FC|NOR> <MRV|MAD> <LCV>
```

If any heuristic is omitted, the default will be used. 
The default board's size can be changed in `Main.py` with the format `(rows, columns, given_values)`
