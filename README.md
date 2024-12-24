
# SNAKE - Snake Game in C

The "SNAKE" project is a simple version of the classic "Snake" game, written in C. The game displays the snake on the screen, and it moves based on user input (up, down, left, right). The goal is to eat the food that appears on the screen without hitting the walls or yourself.

## System Requirements

- Operating System: Windows, Linux, or MacOS
- C Compiler (like GCC)
- `ncurses` library (for text-based graphical interface) - should be installed if not already available

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/snake.git
   ```

2. Navigate to the project directory:
   ```bash
   cd snake
   ```

3. Compile the code:
   ```bash
   gcc -o snake snake.c -lncurses
   ```

4. Run the game:
   ```bash
   ./snake
   ```

## How to Play

- Use the arrow keys:
  - `Up Arrow` to move the snake up
  - `Down Arrow` to move the snake down
  - `Left Arrow` to move the snake left
  - `Right Arrow` to move the snake right
- The goal of the game is to eat the food (represented by `*`) and grow the snake. Avoid hitting the walls or yourself.
- The game ends when the snake hits the wall or itself.

## Features

- Basic text-based graphics using the `ncurses` library
- Dynamic game board management
- Main menu and game-over screen

## Contributing

If you'd like to contribute to the project, feel free to open a Pull Request or submit Issues with suggestions for improvements.

## License

This project is licensed under the MIT License.
