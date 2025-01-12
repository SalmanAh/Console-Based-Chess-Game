# Dodge 'Em Game

This is a simple 2D Dodge 'Em game developed using the **SFML** library in C++ and built in **Visual Studio**. The game was created as an **Object-Oriented Programming (OOP)** project for a university assignment. It involves controlling a player character to dodge incoming obstacles while aiming to achieve the highest score possible.

## Table of Contents
- [Features](#features)
- [Setup and Installation](#setup-and-installation)
- [How to Play](#how-to-play)
- [Controls](#controls)
- [Dependencies](#dependencies)
- [Project Structure](#project-structure)
- [Future Enhancements](#future-enhancements)

---

## Features
- **Dynamic Gameplay**: Randomly spawning obstacles to challenge the player.
- **Scoring System**: Tracks and displays the player's score.
- **Responsive Controls**: Smooth player movement.
- **Custom Graphics**: Eye-catching visuals with textures and shapes.
- **Game Over Screen**: Displays when the player collides with an obstacle.
- **OOP Design**: Organized and modular code structure with classes for game entities.

---

## Setup and Installation
### Prerequisites
1. Install **Visual Studio** with the C++ development workload.
2. Download and install the **SFML** library from [SFML's official website](https://www.sfml-dev.org/).

### Installation Steps
1. Clone or download this repository to your local machine.
2. Set up the SFML library in Visual Studio:
   - Configure the SFML include and library directories in the project's properties.
   - Link the necessary SFML libraries (e.g., `sfml-graphics.lib`, `sfml-window.lib`, `sfml-system.lib`).
3. Build and run the project from Visual Studio.

---

## How to Play
1. Launch the game.
2. Control your player character to avoid obstacles.
3. Survive as long as possible to increase your score.
4. The game ends when your character collides with an obstacle.

---

## Controls
- **Arrow Keys**: Move the player up, down, left, or right.
- **Escape**: Exit the game.

---

## Dependencies
- **SFML**: Used for rendering, input handling, and game mechanics.

Ensure you have the SFML libraries installed and properly configured in your Visual Studio project.

---

## Project Structure
```
DodgeEmGame/
|-- Assets/            # Contains textures, sprites, and other visual elements
|-- Source/
    |-- main.cpp       # Entry point of the application
    |-- Game.cpp       # Core game logic
    |-- Player.cpp     # Player movement and interaction
    |-- Obstacle.cpp   # Obstacle generation and behavior
|-- Include/
    |-- Game.h         # Game class header
    |-- Player.h       # Player class header
    |-- Obstacle.h     # Obstacle class header
|-- README.md          # This file
|-- DodgeEm.sln        # Visual Studio solution file
```

---

## Future Enhancements
- **Multiple Levels**: Introduce levels with increasing difficulty.
- **Power-Ups**: Add power-ups for temporary invincibility or bonus points.
- **High Score Tracker**: Save and display the highest score.
- **Multiplayer Mode**: Add support for two players.
- **Enhanced Graphics**: Use advanced textures and animations.

---

Enjoy playing the game and feel free to contribute or suggest improvements!
