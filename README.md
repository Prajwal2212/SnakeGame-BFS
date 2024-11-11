# SnakeGame-BFS
## Everyone's favourite OG Snake game but solved through Breadth-First-Search Algorithm in python.

## Installation
Clone the repository using git:
```bash
git clone https://github.com/Prajwal2212/SnakeGame-BFS.git
cd SnakeGame-BFS
```

## Project Description: Snake Pathfinder Using BFS
This project is a Python-based Snake game implementation that incorporates a pathfinding algorithm using Breadth-First Search (BFS) to guide the snake to its target (typically food) within the game grid. The game environment and settings are managed through separate modules, enabling easy customization of parameters such as screen dimensions and movement speed. The BFS algorithm allows the snake to navigate the game board automatically by finding the shortest path to food, making it an AI-driven game. The project consists of three main files:\

### play.py:-
This file serves as the main game loop, managing the initialization, game state updates, rendering, and event handling. It integrates the BFS algorithm from snake.py to determine the snake's movement toward the target, adjusting direction accordingly. It also checks for game-over conditions, such as self-collision or boundary collision.

### settings.py :-
This configuration file defines game parameters, including screen width, screen height, and block size. These settings allow for easy adjustments to the game's layout, making it adaptable to various grid sizes and resolutions. This modular design provides flexibility for testing different game configurations.

### snake.py :-
This file implements the Snake class and the BFS algorithm. The class manages the snake's properties, including its position, direction, and growth after eating food. The BFS function finds the shortest path from the snake’s head to the food, updating the direction to keep the snake moving optimally within the grid without colliding with itself.\

This project demonstrates pathfinding techniques within a grid-based game, making it useful for learning and experimenting with BFS and other AI pathfinding algorithms. ​
