# sudokuSolver
Sudoku solver using backtracking
Basically in sudoku, we want to be able to solve a sudoku puzzle given an input like this, which represents a sudoku board:
[[x00, x01, x02, x03... x08],
 [x10, x11, x12, x13... x18],
 ...
 [x80, x81, x82, x83... x88]]
 
These x_rc values correspond to the value at the rth row, cth column (starting with 0-index). These values could be empty (we will represent this with -1)

So for example,

[[-1,  1,  5, ...],
 [-1, -1, -1, ...],
 [ 6, -1, -1, ...]
 ...]
 
would represent a board like this:

| _ 1 5 _ _ _ _ _ _ |
| _ _ _ _ _ _ _ _ _ |
| 6 _ _ _ _ _ _ _ _ |
  ....
  
