# Dino Game

This is a 2D side-scroller game developed in Python using the Pygame library, inspired by the Chrome Dinosaur Game. The objective is to control a dinosaur, make it jump over obstacles, and survive as long as possible.

## Game Features

- **Jumping Dinosaur**: Avoid cacti and flying dinosaurs by jumping over them.
- **Dynamic Obstacles**: Randomized obstacles that increase in speed as the game progresses.
- **Score Tracking**: Earn points for each obstacle passed and receive a sound notification every 100 points.
- **Sound Effects**: Jump, score, and collision sound effects for a more immersive experience.
- **Game Over Screen**: Displays "Game Over" and allows restarting by pressing space.

## Installation

1. **Clone this repository**:
   ```bash
   git clone https://github.com/D3hac/dynogame.git
   ```
   
2. **Navigate to the project directory**:
   ```bash
   cd dynogame
   ```

3. **Install dependencies**:
   Make sure you have [Pygame](https://www.pygame.org/news) installed. If not, install it using pip:
   ```bash
   pip install pygame
   ```

## Running the Game

To start the game, run the following command:

```bash
python DinoGame.py
```

## Controls

- **Spacebar**: Jump
- **Spacebar after Game Over**: Restart the game

## Code Overview

### Key Files

- `DinoGame.py`: Main game logic with classes for `Dino`, `Clouds`, `Floor`, `Cactus`, and `FlyingDino`.
- `image/Spritesheet.png`: Spritesheet for the dinosaur and obstacles.
- `sound/`: Contains sound effects for jump, score, and collision.

### Main Classes

- `Dino`: Handles the dinosaur character's animations and jump functionality.
- `Clouds`, `Floor`: Background elements to enhance visual dynamics.
- `Cactus`, `FlyingDino`: Obstacles that the dinosaur must avoid.

### Game Mechanics

- **Obstacle Collision**: The game ends when the dinosaur collides with an obstacle.
- **Increasing Difficulty**: The game speed increases by 1 every 100 points, making it more challenging over time.

## Future Improvements

Potential enhancements include adding more obstacle types, power-ups, and varying difficulty levels.

## License

This project is for educational purposes and is not intended for commercial use. 

