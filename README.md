# Tic-Tac-Toe-in-Python
A tic-tac-toe game in Python for two players. The game uses a 3x3 grid and checks for wins, draws and valid moves. You need Python 3 to run the game. Download the code and play in your terminal or IDE. Have fun! 😊

This is a simple Python project of a tic-tac-toe game that can be played against another human player. The game uses a 3x3 grid and the players take turns to mark X or O on the board. The first player to get three marks in a row, column or diagonal wins the game. The game also checks for valid moves and draws.

## Requirements

To run the game, you need Python 3 installed on your system. You can download it from [here](https://www.python.org/downloads/).

## Usage

You can download the source code from this repository and execute it in your terminal or IDE. To run the game in the terminal, navigate to the folder where you saved the code and type:

```bash
python tic_tac_toe.py
```

The game will display the board and prompt you to enter a value between 0 and 8, corresponding to the position on the board. For example, 0 is the top-left corner and 8 is the bottom-right corner. You can only enter a value that is not already marked by X or O. The game will alternate between X and O until there is a winner or a draw. The game will announce the result and end.

## Example

Here is an example of how the game looks like in the terminal:

```
Welcome to Tic Tac Toe
0 | 1 | 2 
--|---|---
3 | 4 | 5 
--|---|---
6 | 7 | 8 
X's Chance
Please enter a value: 0
X | 1 | 2 
--|---|---
3 | 4 | 5 
--|---|---
6 | 7 | 8 
O's Chance
Please enter a value: 4
X | 1 | 2 
--|---|---
3 | O | 5 
--|---|---
6 | 7 | 8 
X's Chance
Please enter a value: 8
X | 1 | 2 
--|---|---
3 | O | 5 
--|---|---
6 | 7 | X 
O's Chance
Please enter a value: 6
X | 1 | 2 
--|---|---
3 | O | 5 
--|---|---
O | 7 | X 
X's Chance
Please enter a value: 2
X Won the match
X | 1 | X 
--|---|---
3 | O | 5 
--|---|---
O | 7 | X 
Match over
```
