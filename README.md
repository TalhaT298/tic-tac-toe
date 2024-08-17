## Tic Tac Toe- Game

## Description

Fimple Case 1 is a simple React-based Tic-Tac-Toe game that allows users to play against each other. The game provides an interactive interface where users can choose their player, make moves, and reset the game.

## Features

- **Player Selection**: Choose between Player 1 and Player 2.
- **Game Mechanics**: Click on a cell to place your mark (X or O).
- **Game Reset**: Restart the game at any time.
- **Player Status**: Displays the current player and their mark.

## Installation

1. Clone the repository:

    ```bash
    git clone <repository-url>
    ```

2. Navigate to the project directory:

    ```bash
    cd fimple-case1
    ```

3. Install the dependencies:

    ```bash
    npm install
    ```

## Usage

1. Start the development server:

    ```bash
    npm start
    ```

2. Open your browser and go to `http://localhost:3000`.

## Components

- **App**: The main component that renders `Homepage` and `Footer`.
- **Homepage**: Manages the game state and handles player interactions.
- **Main**: The main game board with buttons representing each cell.
- **FinalResult**: Displays the final result of the game.

## Project Structure

- **src/**
  - **components/**
    - `Homepage.js`: Contains the game logic and player selection.
    - `Main.js`: Renders the game board and handles cell interactions.
    - `FinalResult.js`: Displays the outcome of the game.
  - `App.js`: The root component that renders the `Homepage` and `Footer`.
  - `index.js`: Entry point of the React application.
  - `App.css`: Contains the styling for the app.

## Dependencies

- `react`: ^18.2.0
- `react-dom`: ^18.2.0
- `react-scripts`: 5.0.1
- `@testing-library/react`: ^13.3.0
- `@testing-library/jest-dom`: ^5.16.5
- `@testing-library/user-event`: ^13.5.0
- `web-vitals`: ^2.1.4

## Contributing

Feel free to open an issue or submit a pull request if you'd like to contribute to the project.

### XOX v3 (Responsive) : [Click to PLAY](https://tic-tac-toe-tt.netlify.app/)
