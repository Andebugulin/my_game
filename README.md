# 🌀 Robanization

Welcome to **Robanization**, powered by `pygame`. Unique gaming experience with the ability to design your own levels.

## 🛠️ Installation

Before running the game, make sure you have all the necessary dependencies installed. Here's how:

1. Create and activate your virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## 🧙‍♂️ How to Play

To start the game, simply run the `main` function:

```bash
python main.py
```

### Controls

- **Escape**: Quit the game
- **Mouse Clicks**: Navigate the menu options

## 📜 Game Features

- **Interactive Menu**: Choose between Play, Rules, or Quit from a beautifully designed menu.
- **Dynamic Levels**: The game levels are loaded randomly from text files, feel free to play with level setups and create new levels!
- **Enemies and Obstacles**: Encounter water and tornado obstacles as you progress through the game, later maybe I will add some new mobs if I have a will.

## |~| Game Mechanics

The game is built using `pygame` and includes the following key mechanics:

- **Custom Level Loading**: Levels are dynamically loaded from external files and combined to generate unique maps.
- **Menu System**: A custom sprite-based menu system lets you start the game, view rules, or quit.
- **Interactive Obstacles**: Randomly animated tornadoes and water elements provide dynamic challenges.

## |-| Assets

The game makes use of custom image assets for the menu, game tiles, and obstacles. These include:

- `start.png`: Start button for the main menu
- `rule.png`: Rules button for the main menu
- `quit.png`: Quit button for the main menu
- `tornado.png`: Tornado obstacle
- `water.png`: Water obstacle
- `instructions.png`: Game instructions

Make sure these assets are present in your `/data` folder, if you want to add something more.

## |+| Code Overview

The game loop is structured as follows:

- **Main Game Loop**: Handles menu interactions and gameplay.
- **Menu Class**: Handles the display and interaction of menu buttons.
- **Level Class**: Manages the loading and running of game levels.
- **Obstacle Classes**: Includes water and tornado elements with custom behaviors.

## 🔗 License - unlicensed

Feel free to use and modify this code for your own projects.
