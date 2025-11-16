# Memory Game

A simple and fun memory game built with React and Vite. Test your memory by matching pairs of cards!

## Live Demo

You can play the live version of the game here: [Memory Game Demo](https://69197f7e872fbccd34a26a0c--soft-pavlova-b1122e.netlify.app/)


## Features

- **Interactive Gameplay:** Click to flip cards and find matching pairs.
- **Score and Move Tracking:** Keep track of your score and the number of moves you've made.
- **Responsive Design:** Playable on different screen sizes.
- **Reset Functionality:** Start a new game at any time.

## Tech Stack

- **Frontend:** React
- **Build Tool:** Vite
- **Styling:** CSS

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

Make sure you have Node.js and npm (or yarn) installed on your system.

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/get-npm) (comes with Node.js)

### Installation

1.  Clone the repository:
    ```bash
    git clone https://github.com/your-username/memory-game.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd memory-game
    ```
3.  Install the dependencies:
    ```bash
    npm install
    ```

### Running the Development Server

To start the development server, run the following command:

```bash
npm run dev
```

This will start the application in development mode. Open [http://localhost:5173](http://localhost:5173) (or the address shown in your terminal) to view it in your browser.

### Building for Production

To create a production build of the application, run:

```bash
npm run build
```

This will create a `dist` folder with the optimized and minified files for production.

## Project Structure

The project has a clear and organized structure:

```
game/
├── public/
│   └── vite.svg
├── src/
│   ├── components/
│   │   ├── Card.jsx
│   │   ├── GameHeader.jsx
│   │   └── WinMessage.jsx
│   ├── hooks/
│   │   └── useGameLogic.js
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── .gitignore
├── index.html
├── package.json
└── vite.config.js
```

-   **`src/components`**: Contains the reusable React components for the game (`Card`, `GameHeader`, `WinMessage`).
-   **`src/hooks`**: Holds custom React hooks, with `useGameLogic.js` containing the core game logic.
-   **`src/App.jsx`**: The main application component that assembles the game.
-   **`src/main.jsx`**: The entry point of the React application.
-   **`public/`**: Contains static assets.

## How to Play

1.  The game starts with all cards face down.
2.  Click on a card to flip it over.
3.  Click on a second card to see if it matches the first one.
4.  If the cards match, they will remain face up.
5.  If they don't match, they will be flipped back over after a short delay.
6.  The game is won when all pairs have been matched.
7.  You can reset the game at any time by clicking the "Reset" button.

Enjoy the game!
