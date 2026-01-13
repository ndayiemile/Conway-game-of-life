
# Conway's Game of Life

**Note:** This project was developed as an in-class assignment.

This is a Java implementation of Conway's Game of Life, a cellular automaton devised by mathematician John Conway. The game consists of a grid of cells that evolve through generations according to a set of simple rules.

## Features
- Interactive user interface
- Customizable initial patterns (e.g., X-pattern)
- Step-by-step simulation
- Modular code structure (Cell, Grid, Game, UserInterface, etc.)

## Project Structure
- `Cell.java` - Represents a single cell in the grid.
- `Grid.java` - Manages the grid of cells and their states.
- `Game.java` - Controls the game logic and simulation steps.
- `UserInterface.java` - Handles user interaction and display.
- `Life.java` - Entry point for running the game.
- `Support.java` - Utility and helper functions.
- `App.java` - (in `src/`) May contain additional application logic.
- `simple.init`, `X-pattern.init` - Example initial pattern files.

## How to Run
1. **Compile the code:**
	```sh
	javac *.java
	```
	or, if using the `src/` directory:
	```sh
	javac src/*.java
	```
2. **Run the game:**
	```sh
	java Life
	```
	or, if the main class is in `src/`:
	```sh
	java -cp src App
	```

## Custom Patterns
You can create your own initial patterns by editing or adding `.init` files. The format should match the examples provided.

## License
This project is for educational purposes.
