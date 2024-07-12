# Snake Game using Python and Turtle

This is a classic Snake game implemented in Python using the Turtle graphics library. The game includes a snake that moves around the screen, eating food to grow in length. The goal is to avoid collisions with the walls or the snake's own body while maximizing your score.

## Components

### `main.py`

This file sets up the game environment, including initializing the screen, creating the snake, managing collisions, and updating the game state.

### `snake.py`

Contains the Snake class that defines the behavior and appearance of the snake. It handles movement, growth when eating food, and resetting the game when a collision occurs.

### `food.py`

Defines the Food class, responsible for generating food items (blue circles) at random locations on the screen. The snake consumes these to increase its length and score.

### `scoreboard.py`

Manages the game's scoreboard using the Scoreboard class. It tracks and displays the player's current score and highest score achieved, storing the highest score in a text file (`data.txt`).

## Instructions

1. **Controls:**
   - Use the arrow keys (`Up`, `Down`, `Left`, `Right`) to control the snake's direction.
   - The snake moves automatically at a fixed speed.

2. **Game Rules:**
   - The snake grows in length each time it consumes food (`blue circles`).
   - Avoid collisions:
     - **With Walls:** If the snake hits the screen's boundaries, the game resets.
     - **With Itself:** If the snake collides with its own body segments, the game resets.

3. **Scoring:**
   - Each food item consumed increases the score by 1.
   - The highest score achieved is saved and displayed on the scoreboard.

4. **Resetting:**
   - Click the `Restart` button to reset the game and start over.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/CPoooo/snake-game.git
   cd snake-game
   ```

2. Ensure you have Python installed on your system.

3. Run the game:
   ```bash
   python main.py
   ```
