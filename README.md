# Snake Game

This is a simple Snake game implemented using Python and the Tkinter library for the GUI. The player controls a snake, and the objective is to eat food that appears on the screen, which causes the snake to grow in length. The game ends if the snake collides with itself or the boundaries of the game window.

## Features

- Basic Snake game mechanics.
- Use arrow keys to control the snake's direction.
- Score tracking.

## Requirements

- Python 3.x
- Tkinter library (usually included with standard Python installations)

## How to Run

1. Make sure you have Python installed on your machine.
2. Save the script to a file, for example, `snake_game.py`.
3. Open a terminal or command prompt.
4. Navigate to the directory where you saved the script.
5. Run the script using the command `python snake_game.py`.
6. The game window will open, and you can start playing using the arrow keys.

## Code Overview

The main functionality is provided by the `Snake` and `Food` classes, and various functions to handle the game logic.

### Snake Class

```python
class Snake:
    def __init__(self):
        self.body_size = BODY_PARTS
        self.coordinates = []
        self.squares = []

        for i in range(0, BODY_PARTS):
            self.coordinates.append([0, 0])

        for x, y in self.coordinate
