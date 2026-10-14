# 👾 Space Invaders

A classic arcade-style Space Invaders game created from scratch using Python and Pygame for my Computer Technology assessment.

Take control of a spaceship, defend against waves of invading aliens, and aim for the highest score before your defences are overwhelmed.

## 🚀 Features

- **Classic arcade gameplay:** Move your spaceship, fire lasers, and fight incoming alien waves.
- **Increasing difficulty:** Face a greater challenge as the game progresses.
- **Responsive controls:** Move and shoot using straightforward keyboard controls.
- **Score and health tracking:** Monitor your score and remaining lives during gameplay.
- **High-score saving:** Try to beat your previous best score.
- **Retro presentation:** Pixel-style graphics and sound effects inspired by classic arcade games.

## 🎮 Controls

The game is played using the keyboard.

| Action | Key |
| --- | --- |
| Move left | Left arrow |
| Move right | Right arrow |
| Fire laser | Spacebar |
| Pause game | Escape |

## 🛠️ Prerequisites and Technologies

The game uses:

- **Language:** Python
- **Game library:** Pygame

Python and Pygame must be installed before running the game.

## 📥 Installation and Setup

### 1. Download the repository

On this repository’s GitHub page, select **Code → Download ZIP**, then extract the downloaded folder.

### 2. Install Pygame

Open a terminal and run:

```bash
python -m pip install pygame
```

### 3. Launch the game

Open a terminal in the extracted project folder and run:

```bash
python main.py
```

Keep the project files and any included asset folders together so the game can access its resources.

## 🕹️ How to Play

Move your spaceship left and right and fire lasers at the alien enemies. Avoid incoming attacks and use the defensive obstacles for protection.

Destroy aliens to increase your score and survive as the difficulty increases. Keep track of your remaining lives and aim to beat the saved high score.

## 📂 Project Structure

```text
├── alien.py          # Alien enemy code
├── game.py           # Main gameplay logic
├── highscore.txt     # Saved high-score data
├── laser.py          # Laser projectile code
├── main.py           # Game entry point
├── obstacle.py       # Defensive obstacle code
├── spaceship.py      # Player spaceship code
└── README.md         # Project information and instructions
```
