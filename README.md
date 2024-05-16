
# Connect Four with Minimax AI

This project implements a Connect Four game using Python and Pygame library, featuring an AI opponent powered by the Minimax algorithm with alpha-beta pruning.


## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Game Controls](#game-controls)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Connect Four is a classic two-player game where the objective is to be the first to form a horizontal, vertical, or diagonal line of four of one's own discs. This implementation allows you to play against an AI opponent that uses the Minimax algorithm with alpha-beta pruning to make strategic moves.

## Features

- Interactive graphical user interface using Pygame.
- AI opponent with Minimax algorithm and alpha-beta pruning for efficient move selection.
- Calculating Reduction in Average Branching Factor.
- Sound effects and background music during gameplay.
- Player vs. AI mode.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/OmarrMoustafa/ConnectFourAi.git
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the game:
   ```bash
   python ConnectFourAi.py
   ```

## Usage

Upon running the game, you can play against the AI opponent by taking turns to drop your pieces into the board columns. The AI will respond with calculated moves based on the Minimax algorithm.

## Game Controls

- **Mouse Movement**: Position the cursor to select a column for dropping the piece.
- **Mouse Click**: Drop the piece into the selected column.
- **Exit Game**: Click the close button (X) on the window to exit the game.

## Contributing

Contributions are welcome! Feel free to fork this repository, make improvements, and submit pull requests.

## License

This project is licensed under the [MIT License](LICENSE).

---
