# 🔥 Fiery Flappy Bird --- Browser-Based Arcade Game

Fiery Flappy Bird is a fully functional browser-based arcade game
inspired by the classic Flappy Bird. The game is built using pure HTML,
CSS, and JavaScript without any external libraries or frameworks.

The project demonstrates core game development concepts including
physics simulation, collision detection, game state management, dynamic
obstacle generation, and score tracking. It is designed as a standalone
frontend game that runs directly in the browser.

------------------------------------------------------------------------

# 📌 Overview

Fiery Flappy Bird provides an interactive gaming experience where the
player controls a bird navigating through pipes while avoiding
collisions. The game includes multiple difficulty levels, a lives
system, score tracking, and accessibility features.

This project focuses on implementing a complete game system using
fundamental frontend technologies.

------------------------------------------------------------------------

# 🎯 Objectives

-   Build a complete browser-based game using vanilla JavaScript
-   Implement physics-based bird movement
-   Implement collision detection system
-   Create dynamic obstacle generation
-   Design structured game state management
-   Implement scoring and difficulty system
-   Provide accessibility support

------------------------------------------------------------------------

# 🧠 Architecture Diagram

    +--------------------------------------------------+
    |                     USER INPUT                   |
    |            (Keyboard / Mouse Click)             |
    +---------------------------+----------------------+
                                |
                                v
    +--------------------------------------------------+
    |                  INPUT HANDLER                  |
    |         Handles user interaction events         |
    +---------------------------+----------------------+
                                |
                                v
    +--------------------------------------------------+
    |                 GAME ENGINE LOOP                |
    |         Continuous update and rendering         |
    +---------------------------+----------------------+
                                |
                                v
    +--------------------------------------------------+
    |                 PHYSICS SYSTEM                  |
    |        Applies gravity and velocity logic      |
    +---------------------------+----------------------+
                                |
                                v
    +--------------------------------------------------+
    |               COLLISION DETECTION              |
    |       Detects bird and obstacle collisions     |
    +---------------------------+----------------------+
                                |
                                v
    +--------------------------------------------------+
    |                SCORE MANAGEMENT                |
    |           Tracks score and best score          |
    +---------------------------+----------------------+
                                |
                                v
    +--------------------------------------------------+
    |                GAME STATE MANAGER              |
    |   Controls start, pause, restart, game over    |
    +---------------------------+----------------------+
                                |
                                v
    +--------------------------------------------------+
    |               RENDERING SYSTEM                |
    |        Updates game elements in browser        |
    +--------------------------------------------------+

------------------------------------------------------------------------

# 📂 Project Structure

    Fiery-Flappy-Bird/
    │
    ├── my game.html
    │   ├── HTML structure
    │   ├── CSS styling
    │   └── JavaScript game logic
    │
    ├── README.md
    │
    └── LICENSE

------------------------------------------------------------------------

# 🚀 Features

## Core Gameplay

-   Gravity-based bird movement
-   Upward movement on user input
-   Dynamic pipe generation
-   Collision detection
-   Real-time gameplay

## Difficulty Modes

-   Easy mode
-   Medium mode
-   Hard mode
-   Custom difficulty mode

Custom mode allows adjustment of:

-   Pipe gap
-   Pipe speed

## Lives System

-   Player starts with multiple lives
-   Game ends only after all lives are lost

## Score System

-   Real-time score tracking
-   Best score tracking
-   Best score reset feature

## Game State Management

-   Start screen
-   Game screen
-   Pause functionality
-   Restart functionality
-   Game over screen

## Accessibility Feature

-   Colorblind mode support

------------------------------------------------------------------------

# ⚙️ Installation

Clone the repository:

    git clone https://github.com/SaiKarthik547/Fiery-Flappy-Bird.git

Navigate to directory:

    cd Fiery-Flappy-Bird

Run the game:

Open `my game.html` in any web browser.

------------------------------------------------------------------------

# ▶️ Usage

-   Press Spacebar or Click to make bird jump
-   Avoid pipes
-   Score increases as pipes are passed
-   Game ends when lives reach zero

------------------------------------------------------------------------

# 🛠️ Technologies Used

Programming Languages:

-   HTML5
-   CSS3
-   JavaScript

Platform:

-   Web Browser

Architecture:

-   Game loop architecture
-   Event-driven programming
-   Physics simulation

------------------------------------------------------------------------

# 🔮 Future Improvements

-   Canvas-based rendering
-   Mobile support
-   Sound effects
-   Animations
-   Improved graphics
-   Modular code structure

------------------------------------------------------------------------

# 👨‍💻 Author

Sai Karthik

GitHub: https://github.com/SaiKarthik547

------------------------------------------------------------------------

# 📜 License

This project is licensed for educational and personal use.

------------------------------------------------------------------------

# ⭐ Project Purpose

This project demonstrates frontend engineering skills, browser-based
game development, and implementation of core game mechanics using
vanilla JavaScript.
