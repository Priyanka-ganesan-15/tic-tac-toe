
# Tic-Tac-Toe Game

A simple, interactive Tic-Tac-Toe game implemented with JavaScript, HTML, and CSS. The game allows two players to play against each other, taking turns to place their marks on a 3x3 grid until one player wins or the game ends in a tie.

## Features

- Interactive UI with real-time updates
- Displays the current player's turn
- Highlights the winning combination
- Option to restart the game

## Project Structure

- `index.html`: The main HTML file containing the structure of the game board and UI elements.
- `style.css`: The CSS file for styling the game.
- `game.js`: The JavaScript file containing the game logic.
- `gameView.js`: The JavaScript file handling the user interface and interactions.
- `main.js`: The main JavaScript file to initialize and control the game.

## Getting Started

### Prerequisites

Ensure you have a modern web browser installed (e.g., Google Chrome, Mozilla Firefox).

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/tic-tac-toe.git
    cd tic-tac-toe
    ```

2. **Open `index.html`** in your web browser to start the game.

### Usage

- Click on any tile to make a move.
- The game alternates turns between "X" and "O".
- The status above the game board will show whose turn it is, if someone has won, or if the game is a tie.
- Click the restart button to start a new game.

## Code Overview

### `game.js`

Contains the `Game` class, which handles the game logic:
- **`constructor()`**: Initializes the game state.
- **`nextTurn()`**: Switches the turn between "X" and "O".
- **`makeMove(i)`**: Places a mark on the board and checks for a winner.
- **`findWinningCombination()`**: Checks the board for any winning combinations.
- **`isInProgress()`**: Checks if the game is still in progress.

### `gameView.js`

Contains the `GameView` class which manages the UI:
- **`constructor(root)`**: Sets up the game UI and event listeners.
- **`update(game)`**: Updates the UI based on the current game state.
- **`updateTurn(game)`**: Updates the current turn display.
- **`updateStatus(game)`**: Updates the game status display.
- **`updateBoard(game)`**: Updates the board tiles and highlights the winning combination.


