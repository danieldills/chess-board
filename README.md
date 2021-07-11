# Numpy Arrays

## Author: Daniel Dills

## Overview

Today we’ll be constructing chess boards like it’s 1980.

No prebuilt images, just the power of arrays and pixel art.

## Links

- [See the Code](chess_board.ipynb)
- [Pull Request](https://github.com/danieldills/chess-board/pull/1)

## Feature Tasks and Requirements

- Chess board is an 8 by 8 grid of alternating black and white squares. The queens are red and blue squares.

- Each board will have one red and one blue queen at different coordinates. In addition to displaying the board you’ll need to identify if the queens are “under attack” based on their coordinates.

  - Define a ChessBoard class - should contain an 8x8 grid - Each cell in grid should have a color represented in RGB format. - black = (0,0,0) - white = (1,1,1) - blue = (0,1,1) - red = (1,.2,0)
    - should have add_red method that accepts a row and column as input which colors corresponding cell.
    - should have add_blue method that accepts a row and column as input which colors corresponding cell.
    - should have render method that displays the chess board on screen with red and blue shown in correct locations
    - should have is_under_attack method that return boolean if red is under attack by a blue piece horizontally, vertically or diagonally

## User Acceptance Tests

- queens on same row should be “under attack”
- queens on same column should be “under attack”
- queens on same diagonal should be “under attack”
- queens with any other coordinates should NOT be “under attack”

- NOTE: Include assert statements directly in your notebook verifying the behavior above.

## Collaborations

- This lab was done in collaboration with [Davee Sok](https://github.com/daveeS987) and Wondwosen.

## Article Credit

[Print Checkerboard Pattern using Numpy](https://www.geeksforgeeks.org/python-program-print-checkerboard-pattern-nxn-using-numpy/)

[Check if a Queen can attack an oppenent](https://www.geeksforgeeks.org/check-if-a-queen-can-attack-a-given-cell-on-chessboard/)
