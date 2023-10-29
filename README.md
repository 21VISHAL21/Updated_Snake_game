# Updated_Snake_game
This is a simple Snake Game implemented in Python using the Turtle graphics library. The game consists of four main components: `main.py`, `scoreboard.py`, `snake.py`, and `food.py`. The game allows a snake to move around the screen, eat food, and keep track of the player's score. If the snake collides with the wall or itself, the game will end.

## How to Play

1. Use the arrow keys (`Up`, `Down`, `Left`, `Right`) to control the snake's direction.
2. Move the snake to eat the blue food that appears on the screen.
3. The snake's length will increase each time it eats the food, and your score will increase.
4. Avoid hitting the wall or running into the snake's own body to prevent the game from ending.

## Files

### main.py

This is the main script that runs the game. It creates the game window, initializes the snake, food, and scoreboard, and handles game logic. The game loop keeps running until it's over.

### scoreboard.py

This script defines the `Scoreboard` class, which keeps track of the player's score and the high score. It also handles score updates and resets.

### snake.py

This script defines the `Snake` class, which manages the snake's behavior, including its movement and collision detection. It also allows for extending the snake's length when it eats the food.

### food.py

This script defines the `Food` class, which creates the blue food that the snake needs to eat. It refreshes the food's position when it is eaten by the snake.

## How to Run

1. Make sure you have Python installed on your system.
2. Clone or download this repository to your computer.
3. Open a terminal or command prompt and navigate to the directory where you have the game files.
4. Run the game using the following command:

```bash
python main.py
```

## Dependencies

The game uses the `turtle` library, which is a built-in library for creating simple graphics and games in Python.

## High Score

The game also keeps track of the high score. If you beat your previous high score, it will be updated and saved to a file named `data.txt`.

Enjoy playing the Snake Game! If you have any questions or suggestions, feel free to reach out. Have fun!
