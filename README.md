# 🎮 Tic-Tac-Toe Game

## 📖 Description
This is a simple console-based Tic-Tac-Toe game implemented in Java. The game allows a player to compete against a computer opponent.

## ✨ Features
- 🖥️ Console-based user interface
- 👤 Player vs Computer gameplay
- 🔢 Simple input system using numbers 1-9 for board positions
- 🤖 Random move generation for the computer player

## 🕹️ How to Play
1. Run the game
2. Enter a number between 1-9 to place your 'X' on the board
3. The computer will automatically make its move
4. Continue until the game is won or ends in a draw

## 🏗️ Code Structure
- `TicTacToe` class: Main game logic
- `printGameBoard`: Displays the current state of the game board
- `placePiece`: Places a player or CPU piece on the board
- `checkWinner`: (In progress) Will check for a winner

## 💻 How to Run
1. Compile the Java file:

2. Run the compiled class:
## 🚧 Current Limitations
- The game doesn't yet check for a winner or a draw
- The computer's moves are completely random and not strategic
- There's no input validation to prevent overwriting occupied spaces

## 🔮 Future Improvements
- Implement win condition checking
- Add draw condition checking
- Improve computer AI for more challenging gameplay
- Add input validation to prevent illegal moves
- Implement a score tracking system
- Allow players to choose their symbol ('X' or 'O')
- Add an option for two human players

## 🐛 Known Issues
- The game currently runs in an infinite loop
- The `checkWinner` method is incomplete

## 🤝 Contributing
Feel free to fork this project and submit pull requests with improvements!

Enjoy the game! 🎉
