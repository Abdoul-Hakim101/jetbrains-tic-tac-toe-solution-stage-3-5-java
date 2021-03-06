# jetbrains-tic-tac-toe-solution-stage-3-5-java
 Tic Tac Toe stage 3/5 
Description

In this stage, we’re going to analyze the game state to determine if either of the players has already won the game or it is still ongoing, if the game is a draw, or if the user has entered an impossible game state (two winners, or with one player having made too many moves).

Objectives

In this stage, your program should:

1.Take a string entered by the user and print the game grid as in the previous stage.
2.Analyze the game state and print the result. Possible states:
•Game not finished when neither side has three in a row but the grid still has empty cells.
•Draw when no side has a three in a row and the grid has no empty cells.
•X wins when the grid has three X’s in a row.
•O wins when the grid has three O’s in a row.
•Impossible when the grid has three X’s in a row as well as three O’s in a row, or there are a lot more X's than O's or vice versa (the difference should be 1 or 0; if the difference is 2 or more, then the game state is impossible).

In this stage, we will assume that either X or O can start the game.

You can choose whether to use a space or underscore _ to print empty cells.

Examples
The examples below show outputs and analysis results for different game states. Your program should work in the same way.

Notice that after Enter cells: comes the user input.
