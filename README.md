# ReactJS Tic-Tac-Toe Demo

This is a simple Tic-Tac-Toe game built with ReactJS. The project demonstrates the use of React components, state management, and animations to create an interactive and visually appealing game.

## Features

- **Two-player gameplay**: Players take turns selecting squares on the game board.
- **Dynamic player names**: Players can edit their names during the game.
- **Game status**: Displays the active player, winner, or draw status.
- **Game log**: Keeps track of all moves made during the game.
- **Animations**: Includes animations for highlighting the active player, game over screen, and more.
- **Responsive design**: The game is styled to look good on various screen sizes.

## Project Structure
 ├── public/ 
 │ ├── bg-pattern-dark.png 
 │ ├── bg-pattern.png 
 │ ├── game-logo.png 
 ├── src/ 
 │ ├── App.jsx 
 │ ├── index.css 
 │ ├── index.jsx 
 │ ├── winning-combinations.js 
 │ ├── assets/ 
 │ │ └── react.svg 
 │ ├── components/ 
 │ │ ├── GameBoard.jsx 
 │ │ ├── GameOver.jsx 
 │ │ ├── Log.jsx 
 │ │ └── Player.jsx 
 ├── .gitignore 
 ├── index.html 
 ├── LICENSE 
 ├── package.json 
 ├── pnpm-lock.yaml 
 ├── README.md 
 ├── vite.config.js


### Key Files

- **`src/App.jsx`**: The main application component that manages the game state and renders the game board, players, and game log.
- **`src/components/`**: Contains reusable components:
  - `GameBoard.jsx`: Renders the Tic-Tac-Toe board and handles square selection.
  - `GameOver.jsx`: Displays the game over screen with the winner or draw message.
  - `Log.jsx`: Displays the log of all moves made during the game.
  - `Player.jsx`: Displays player information and allows editing player names.
- **`src/winning-combinations.js`**: Defines all possible winning combinations for the game.
- **`src/index.css`**: Contains all the styles for the application, including animations.
- **`vite.config.js`**: Configuration file for Vite, the build tool used in this project.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/reactjs-tic-tac-toe-demo.git
   cd reactjs-tic-tac-toe-demo
   ```
2. Install dependencies:
    ```bash
   pnpm install
   ```
3. Start the development server:
    ```bash
   pnpm run dev
   ```
4. Open the game in your browser at `http://localhost:5173`.

## Scripts
`pnpm run dev`: Starts the development server.

`pnpm run build`: Builds the project for production.

`pnpm run preview`: Previews the production build.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
Built with ReactJS.
Styled with custom CSS and animations.
Powered by Vite for fast development and build.
Enjoy playing Tic-Tac-Toe!