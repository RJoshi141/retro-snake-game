# 🎮 Retro Snake Game 🐍

Welcome to the Retro Snake Game! This repository features a classic Snake game implemented in Python using the Turtle graphics library and the `freegames` module. Dive into this timeless arcade adventure, complete with colorful visuals and a dash of nostalgia.

## 🌟 Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Gameplay](#gameplay)
- [Exercises](#exercises)
- [License](#license)

## 🚀 Introduction

Welcome to the ultimate Retro Snake Game! 🐍🎉 Navigate your snake through the screen, gobbling up delicious food while avoiding those tricky walls and your own tail. Ready to relive the fun of classic arcade gaming? Let’s go!

### 🎬 Gameplay Preview

**Snake Movement and Eating**

Check out this GIF showing our snake slithering and munching on the red food! 🍎

<img src="media/snake-gameplay-1.gif" alt="Snake Movement and Eating" width="400"/>

**Game Over Scenarios**

Oops! 😱 Watch what happens when the snake hits the edge or itself. Be careful out there!

<img src="media/snake-gameplay-2.gif" alt="Game Over" width="400"/>

## 🛠️ Installation

Ready to get started? Here’s how to set up your environment:

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/your-username/retro-snake-game.git
   cd retro-snake-game
   ```

2. **Create a Virtual Environment:**
   ```sh
   python3 -m venv venv
   ```

3. **Activate the Virtual Environment:**
   - On macOS and Linux:
     ```sh
     source venv/bin/activate
     ```
   - On Windows:
     ```sh
     venv\Scripts\activate
     ```

4. **Install Dependencies:**
   ```sh
   pip install freegames
   ```

## 🕹️ Usage

To jump into the action, run the `snake.py` file:

```sh
python snake.py
```

## 🎮 Gameplay

Control your snake with the arrow keys:
- **Right Arrow**: Move right
- **Left Arrow**: Move left
- **Up Arrow**: Move up
- **Down Arrow**: Move down

Your goal? Gobble up the food (red square) that appears randomly. Each bite makes the snake grow longer. The game ends if you crash into the walls or yourself. 

## ✨ Exercises

Feeling adventurous? Try out these fun challenges to enhance the game:

1. **Speed Up or Slow Down:** Change the `ontimer(move, 100)` value to make the snake faster or slower.
2. **Edge Wrapping:** Modify the `inside(head)` function to make the snake wrap around the screen edges.
3. **Move the Food:** Add a feature to randomly reposition the food on the screen.
4. **Mouse Clicks:** Make the snake respond to mouse clicks for a new twist!

## 📜 License

This project is licensed under the [Apache 2.0 License](LICENSE). Check out the `LICENSE` file for more details.

---

Feel free to fork this repo and contribute! Pull requests are welcome. Let’s make this game even more awesome together! 🎉