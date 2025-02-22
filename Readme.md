# Pacman Game

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Installation](#installation)
4. [How to Play](#how-to-play)
5. [Controls](#controls)
6. [Screenshots](#screenshots)
7. [Technologies Used](#technologies-used)
---

## Introduction
This is a classic Pacman game implemented in Java using the `javax.swing` library. The game features Pacman navigating through a maze, collecting food, and avoiding ghosts. The objective is to score as many points as possible by eating all the food while avoiding collisions with ghosts. The game includes multiple levels, power-ups, and a scoring system.

---

## Features
- **Classic Pacman Gameplay**: Navigate Pacman through a maze to collect food and avoid ghosts.
- **Multiple Ghosts**: Four types of ghosts (blue, orange, pink, and red) with random movement patterns.
- **Score System**: Earn points by collecting food.
- **Lives System**: Start with 3 lives; lose a life when colliding with a ghost.
- **Game Over**: The game ends when all lives are lost.
- **Reset Functionality**: Restart the game after losing all lives.
- **Dynamic Movement**: Ghosts and Pacman move smoothly with collision detection.

---

## Installation
### Prerequisites
- **Java Development Kit (JDK)**: Ensure you have JDK installed on your system.
- **Git**: Optional, for cloning the repository.

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/gautamashutoshgautam/Packman.git
   ```
2. Navigate to the project directory
   ```bash
   cd pacman-game
   ```
3. Compile the Java files
   ```bash
   javac -d bin src/*.java
   ```
4. Run the game
   ```bash
   java -cp bin Main
   ```

## How to Play
- The goal is to collect all the food in the maze while avoiding ghosts.

- Use the arrow keys to move Pacman.

- Colliding with a ghost will cost you a life.

- The game ends when all lives are lost or all food is collected.

- After losing all lives, press any key to restart the game.

## Controls
- Arrow Up (↑): Move Pacman upwards.

- Arrow Down (↓): Move Pacman downwards.

- Arrow Left (←): Move Pacman to the left.

- Arrow Right (→): Move Pacman to the right.

## Screenshots

1. Game Start
<img width="605" alt="Screenshot 2025-02-21 at 8 06 48 PM" src="https://github.com/user-attachments/assets/11837fd3-7a49-4df5-8c78-128d00af8cc4" />



2. In Progress
<img width="601" alt="Screenshot 2025-02-21 at 8 05 23 PM" src="https://github.com/user-attachments/assets/07f55c93-d827-4a1f-a2db-14871ced17f0" />



3. Game Over
<img width="604" alt="Screenshot 2025-02-21 at 8 27 20 PM" src="https://github.com/user-attachments/assets/5ccdcf33-2cc7-44f9-9855-176da00a8a6e" />




## Technologies Used
- Java: The core programming language used for the game.

- Java Swing: Used for creating the graphical user interface (GUI).

- AWT (Abstract Window Toolkit): Used for handling graphics and user input.
