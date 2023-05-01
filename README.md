# Snake_game
This is a simple console-based Snake game written in C++. The game is played on a 20x20 grid, where the player controls a snake that moves around and eats food to grow longer. The objective of the game is to get the highest score possible by eating as much food as you can without crashing into any walls or the snake's body.
## How to Play

To start the game, run the program and press any key to begin. You can control the snake's movement using the following keys:

- W: Move up
- A: Move left
- S: Move down
- D: Move right

You can exit the game at any time by pressing the X key.

## How it Works

The game logic is implemented using a series of functions that handle different aspects of the game. The `Setup()` function initializes the game state, including setting the starting position of the snake and the location of the first food item. The `Draw()` function handles rendering the game screen, including drawing the walls, snake, and food items. The `Input()` function handles getting input from the user and updating the direction of the snake accordingly. The `Logic()` function handles updating the game state based on the current direction of the snake, including checking for collisions with walls, food items, and the snake's body.

The game uses ASCII characters to draw the graphics on the console screen. The snake is represented by the letter "O", food items are represented by "@" symbols, and empty spaces are represented by spaces.

## Conclusion

This Snake game is a fun and simple project for anyone looking to practice their C++ programming skills. It demonstrates how to use basic console input/output functions, as well as how to implement game logic using functions and control structures.
