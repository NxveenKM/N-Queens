# N-Queens Problem Solver

This project provides a solution to the N-Queens problem, which is a classic backtracking problem in computer science. The goal is to place N queens on an N×N chessboard such that no two queens threaten each other.

## Problem Description

The N-Queens problem involves placing N queens on a chessboard in such a way that:
- No two queens share the same row.
- No two queens share the same column.
- No two queens share the same diagonal.

The solution should return all distinct solutions to the N-Queens puzzle.

## Functionality

The main function provided in this project is:

```python
class Solution:
    def solveNQueens(self, n: int) -> List[List[str]]:
