# N-Queens
The N-Queens puzzle places N queens on an N×N chessboard so no two queens threaten each other, ensuring no shared row, column, or diagonal. The solution uses recursion:

1. Place a queen on the board.
2. Recursively place the next queen in the next row.
3. Check for conflicts with previously placed queens.
4. Backtrack if conflicts arise.
5. Repeat until all queens are placed without conflicts.
6. Return the board configuration.
