# Python Snake Game 🐍

A classic Snake game implementation using Pygame. This is a modern recreation of the iconic Nokia phone game where players control a snake to eat apples and grow longer while avoiding collisions.

## 🎮 Game Features

- Smooth snake movement with arrow key controls
- Apple collection mechanics that increase snake length
- Collision detection for walls and self-intersection
- Clean and simple visual design
- Consistent game speed and performance

## 🛠️ Technical Details

### Requirements
- Python 3.x
- Pygame library

### Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/snake-game.git
```
2. Install the required dependencies:
```bash
pip install pygame
```
3. Run the game:
```bash
python snake.py
```

### Controls
- ⬆️ Up Arrow: Move snake upward
- ⬇️ Down Arrow: Move snake downward
- ➡️ Right Arrow: Move snake right
- ⬅️ Left Arrow: Move snake left

## 🎯 Game Rules

- Control the snake to eat the apples that appear on the screen
- Each apple eaten makes the snake grow longer
- Game ends if the snake:
  - Hits the walls (screen boundaries)
  - Collides with itself

## 🏗️ Project Structure

The game is built using object-oriented programming with three main classes:
- `SNAKE`: Handles snake movement, growth, and rendering
- `FRUIT`: Manages apple spawning and rendering
- `MAIN`: Controls game logic, collisions, and game over conditions

## 🎨 Graphics
The game uses a simple apple sprite for the fruit. Make sure you have the following file:
- `Graphics/apple.png`


## 🤝 Contributing

Feel free to fork this project and make your own modifications. Some possible enhancements could include:
- Adding a score system
- Implementing different difficulty levels
- Adding sound effects
- Creating a main menu
- Adding different types of food with special effects

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

---

Created with ❤️ using Python and Pygame
