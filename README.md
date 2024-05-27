# Game of Life - with REACT🌟

Welcome to the **Game of Life** implementation using React! This is a cellular automaton devised by the British mathematician John Horton Conway in 1970. It's a zero-player game, meaning that its evolution is determined by its initial state, requiring no further input.

## Description 📜

The Game of Life consists of a grid of cells which can live, die, or multiply based on a few mathematical rules. Each cell interacts with its eight neighbors, which are the cells that are horizontally, vertically, or diagonally adjacent.

### The Rules 📏

1. **Underpopulation**: A living cell with fewer than two living neighbors dies.
2. **Survival**: A living cell with two or three living neighbors lives on to the next generation.
3. **Overpopulation**: A living cell with more than three living neighbors dies.
4. **Reproduction**: A dead cell with exactly three living neighbors becomes a live cell.

## Features and Functions 🔧

- **Interactive Grid**: Click on cells to toggle their state (alive/dead).
- **Start/Stop**: Control the simulation with "Run" and "Stop" buttons.
- **Random Generation**: Populate the grid with a random initial state.
- **Clear Grid**: Reset the grid to an empty state.
- **Adjustable Speed**: Change the interval at which the grid updates.

### Key Functions in the Code

- `makeEmptyBoard()`: Initializes an empty game board.
- `makeCells()`: Creates an array of live cells for rendering.
- `handleClick()`: Toggles the state of a cell when clicked.
- `runGame()`: Starts the simulation.
- `stopGame()`: Stops the simulation.
- `runIteration()`: Advances the game by one iteration based on the rules.
- `calculateNeighbors(board, x, y)`: Calculates the number of live neighbors for a given cell.

## How to Run 🚀

1. Clone the repository:

```sh
   git clone https://github.com/your-username/game-of-life.git
```

2. Navigate to the project directory:

```sh
   cd game-of-life
```

3. Install dependencies:

```sh
   npm install
```

4. Start the application:

```sh
   npm start
```

## Enjoy the Game! 🎉

Feel free to explore, tweak, and enjoy the beauty of Conway's Game of Life!
