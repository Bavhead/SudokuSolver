# SudokuSolver
Multi-algorithmic sudoku solver and generator.

Supports the following algorithms or any combination:
- Brute Force
- Forward Checking (FC)
- Arc Consistency
- Norvig (NOR)
- Minimum Remaining Value w/o Tiebreaker (MRV)
- Minimum Remaining Value w/Tiebreaker (MAD)
- Least Constraining Value (LCV)

To run, call
```
python3 Main.py <path_to_board_text_file_if_any> <FC|NOR> <MRV|MAD> <LCV>
```

If any heuristic is omitted, the default will be used. 
The default board's size can be changed in `Main.py` with the format '(rows, columns, given_values)'
