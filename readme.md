# Ping Pong Game

A classic Pong-style game implemented in Python using the Turtle module.

## Table of Contents

* [Project Description](#project-description)
* [Features](#features)
* [Development Environment](#development-environment)
* [Requirements](#requirements)
* [Installation](#installation)
* [Running the Game](#running-the-game)
* [Controls](#controls)
* [Project Structure](#project-structure)
* [Contribution Guidelines](#contribution-guidelines)

## Project Description

This repository contains a simple two-player Ping Pong (Pong) game built with Python's Turtle graphics library. It demonstrates basic game mechanics such as:

* Ball movement and angle-based trajectory
* Collision detection with paddles and walls
* Keeping and displaying scores
* Resetting the ball upon a miss

## Features

* Smooth paddle controls with keyboard input
* Realistic ball physics (angle reflection on collision)
* Scoreboard display for both players
* Automatic reset of the ball after missing a paddle
* Adjustable ball speed and angle

## Development Environment

* **Operating System:** Arch Linux (also tested on Windows and Linux Mint)
* **IDE:** Visual Studio Code
* **Python Version:** 3.8+
* **Hardware:** Development tested on systems with NVIDIA RTX 3050 GPU (face recognition module, future extension) and typical CPU setups

> Note: The game logic is contained in `ball.py`, `paddle.py`, `scoreboard.py`, and orchestrated by `main.py`.

## Requirements

* Python 3.8 or higher
* Standard library modules:

  * `turtle`
  * `random`
  * `time`

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/ping-pong-game.git
   cd ping-pong-game
   ```
2. (Optional) Create and activate a virtual environment:

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # Linux/macOS
   venv\\Scripts\\activate  # Windows
   ```
3. Ensure you have Python 3.8+ installed:

   ```bash
   python --version
   ```

## Running the Game

From the project root, run:

```bash
python main.py
```

The game window will open. Use the controls below to play.

## Controls

* **Left Paddle (Player 1):**

  * Move Up: `W`
  * Move Down: `S`
* **Right Paddle (Player 2):**

  * Move Up: `Up Arrow`
  * Move Down: `Down Arrow`

## Project Structure

```
ping-pong-game/
├── ball.py        # Ball class: movement, collision, reset
├── paddle.py      # Paddle class: positioning and controls
├── scoreboard.py  # Scoreboard class: tracking and displaying score
└── main.py        # Entry point: game setup and main loop
```

## Contribution Guidelines

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-name`)
3. Make your changes and commit (`git commit -m 'Add feature'`)
4. Push to the branch (`git push origin feature-name`)
5. Open a Pull Request

Please follow standard GitHub workflow and ensure code quality.

