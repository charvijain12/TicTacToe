# TicTacToe
This is a simple Tic-Tac-Toe game written in C programming language. This game can be played by two players on a console.

## How to play
1. The game board is represented by a character array called "square".
2. Players will take turns entering a number that corresponds to the square they want to place their marker in (X or O).
3. The game continues until either one of the players wins or there are no more moves left.
4. The "checkwin" function checks the game board after each move to determine if there has been a win.
5. The "board" function is used to display the game board.
6.The game is played in a loop that continues until the "checkwin" function returns either 0 (draw) or 1 (win).


## How to run
1. Clone the repository: `git clone https://github.com/charvijain12/TicTacToe.git`
2. Navigate to the project directory: `cd TicTacToe`
3. Compile the code: `gcc tictactoe.c -o tictactoe`
4. Run the program: `./tictactoe`


## Contribution
If you want to contribute to this project, feel free to submit a pull request. Any suggestions, improvements, and feedback are welcome!


## License
This project is licensed under the `MIT License` - see the LICENSE file for details.
