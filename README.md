# 🐍 Circular Snake Game - Pygame

Welcome to **Circular-Snake-Pygame**, a fun snake game built using **Pygame** where the snake moves in circular segments! The game features smooth movement, sound effects, and an interactive UI.

## 🛠️ Features
- 🌟 **Circular Snake:** The snake moves with circular segments.
- 🎧 **Sound Effects:** Background music and effects for eating food and game over.
- 🍔 **Random Food Placement:** The food appears at random positions on the screen.
- 🛡️ **Collision Detection:** The game ends when the snake collides with itself.
- 📈 **Score Display:** Keep track of your score as you eat food.

## 📝 Requirements
Make sure you have **Python** installed, and install the required libraries using:

```sh
pip install pygame
```

## 🎮 How to Play
1. Run the game using:
   ```sh
   python circular_snake.py
   ```
2. Control the snake using **Arrow Keys**:
   - ⬆️ **Up Arrow** - Move Up
   - ⬇️ **Down Arrow** - Move Down
   - ⬅️ **Left Arrow** - Move Left
   - ➡️ **Right Arrow** - Move Right
3. Eat the food (🍏) to increase your score.
4. Avoid colliding with yourself!

## 🎤 Sound Effects
- **Background Music:** `background.wav`
- **Food Eating Sound:** `eat_wav.mp3`
- **Game Over Sound:** `game_oversound1.wav`

## 📝 Code Overview
- `random_position()`: Generates a new random position for food.
- `is_collision()`: Checks if the snake collides with food.
- `move()`: Moves the snake in the current direction.
- `draw_snake()`: Draws the snake as circular segments.
- `sel_collision()`: Detects self-collision.
- `show_score()`: Displays the player's score.
- `Game_Over()`: Displays the game over screen.

## ✨ Future Improvements
- Add different game levels (🔹 Easy, 🔸 Medium, 🔷 Hard).
- Implement power-ups (💎 Speed Boost, 🎁 Bonus Points).
- Enhance visuals with animations (🎭).

## 🛠️ Troubleshooting
If you encounter any issues, ensure that:
- You have installed **Pygame** (`pip install pygame`).
- All required sound/image files are in the same directory.
- Your Python version is **3.x**.

## 📢 Contributing
Feel free to **fork** this repository and add your own features! Pull requests are welcome.

## 💎 Credits
- Developed with **Pygame**
- Sound effects and assets from open sources

Enjoy the game! 🚀🎮

