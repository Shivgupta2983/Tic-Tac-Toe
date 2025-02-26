# Tic-Tac-Toe Game 🕹️


## Preview
![alt text](https://github.com/Shivgupta2983/Tic-Tac-Toe/blob/8cff6a84f9926a6fdff46e0d2264d5f8d31b615a/Preview%20Image.png)


## Overview

This is a classic Tic-Tac-Toe game implemented using HTML, CSS, and JavaScript. You can play against a computer AI 🤖 with adjustable difficulty. The game features a clean and user-friendly interface with options to customize your playing experience.

## Features

*   **Play against AI**: Challenge yourself against a computer opponent. 🧠
*   **Adjustable difficulty**: Choose between Easy and Hard AI difficulty levels. 😌 😈
*   **Play as X or O**: Select whether you want to play as X or O (going first). ❌ ⭕
*   **Score tracking**: Keeps track of your wins, losses, and draws against the computer. 🏆
*   **Responsive design**: Playable on various screen sizes. 📱💻
*   **Modal Options**: Options to change difficulty and play mode. ⚙️

## Technologies Used

*   HTML 🖼️
*   CSS 🎨
*   JavaScript 📜

## How to Play

1.  Clone the repository to your local machine. 💻
2.  Open the `index.html` file in your web browser. 🌐
3.  Configure your game preferences using the provided options:
    *   Select the difficulty level (Easy or Hard).
    *   Choose to play as X or O.
4.  Click the "Play" button to start the game. ▶️
5.  Click on an empty cell in the Tic-Tac-Toe grid to make your move. 👆
6.  The computer AI will make its move after you. 🤖
7.  The game continues until either a player wins, or it's a draw. ✅
8.  Click the "Restart Game" button to play again. 🔄

## Game Logic

The JavaScript code implements the core game logic, including:

*   **AI Strategy**: The computer AI uses a `getFirstWithTwoInARow` function to find the best move. The AI will try to win first or block the player from winning. 🤖
*   **Win Condition Check**: The `checkWin` function determines if there is a winner by checking rows, columns, and diagonals. ✅
*   **Grid Management**: The `Grid` object manages the state of the Tic-Tac-Toe board. 🈳
*   **Turn Management**: The `cellClicked` and `makeComputerMove` functions manage the turns of the player and the computer. 🔄

## Code Structure

*   `index.html`: Contains the HTML structure of the game, including the game board, buttons, and modal. 🧱
*   `styles.css`: Contains the CSS styles for the game, including the layout, colors, and fonts. 🎨
*   `script.js`: Contains the JavaScript code for the game logic and user interface. 📜

## Customization

You can customize the game by modifying the following:

*   **CSS styles**: Change the colors, fonts, and layout of the game by editing the `styles.css` file. 🎨
*   **AI difficulty**: Adjust the AI difficulty by modifying the `makeComputerMove` function in the `script.js` file. 🤖
*   **Game messages**: Change the game messages by modifying the text in the `index.html` file. 💬

## Future Enhancements

*   Implement a Minimax algorithm for the AI to improve its decision-making. 🧠
*   Add a two-player mode. 👥
*   Implement a more attractive user interface. ✨
*   Add sound effects and animations. 🔊

## Credits

*   Game Developed by: Shiv Gupta 👨‍💻
*   Inspired by the classic Tic-Tac-Toe game. 💡

## License

[GNU General Public License v3.0](LICENSE) 📝
