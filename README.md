This is a nice sudoku solver made using backtracking algorithms specially recursion, this solver 
has three buttons:
1. Solve
2. Speed Solve.
3. New Board
   How to input and solve:
Select a number and then click any particular square of choice inside the sudoku to insert the number, to deselect the number either click on del button or select a new number and
repeat the process.

    Clicking on solve solves the sudoku board, but it takes some time as an async javascript function is used to explore all possibilities in rows and columns
   and check at every insertion if the new inserted number violates the rules of sudoku or not.

   Clicking on speed solve almost solves the sudoku instantly it doesnt need to wait and sleep function is not called.

Warnings:
1. If same insertions are made in a same row, a warning will be generated.
2. If same insertions are made in a same column, a warning will be generated.
3. If same inserions are made in a square of dimensions 3*3 which is one of the nine sub squares in sudoku, a warning will be generated.
   Link to solver: https://majestic-arithmetic-3d2140.netlify.app/
