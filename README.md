# Flappy Bird (Python Edition)

A clone of the classic Flappy Bird game, built using Python and [pygame](https://www.pygame.org/). Fly the bird through gaps in pipes and try to achieve the highest score!

## Features

- Smooth gameplay and animations
- Multiple bird, background, and pipe sprites
- Sound effects for flapping, scoring, and collisions
- Responsive controls (keyboard and mouse/touch)
- Modular code structure for easy customization

## Getting Started

### Prerequisites

- Python 3.7+
- [pygame](https://pypi.org/project/pygame/)

### Installation

1. ** (Optional but recommended) Create a virtual environment:**
```bash
    python -m venv venv
    venv\Scripts\activate
```
    On macOS/Linux, activate with:
```bash
    source venv/bin/activate
```

2. Clone this repository:
```bash
    git clone https://github.com/yourusername/flappy-bird-python.git
    cd flappy-bird-python
```

3. Install dependencies:
```bash
    pip install pygame
```

### Running the Game

Run the main script:
```bash
python [main.py](http://_vscodecontentref_/0)
```

### Controls
Spacebar / Up Arrow: Flap the bird
Mouse Click / Touch: Flap the bird
Esc: Quit the game

### Project Structure
main.py — Entry point for the game
src/ — Source code
flappy.py — Main game loop and logic
entities/ — Game objects (player, pipes, floor, etc.)
utils/ — Utility functions, configuration, assets loader
assets/ — Sprites and audio files

### Credits
```bash
Sprites and sounds adapted from the original Flappy Bird game.
Developed by Gaurang Gautam.
```

### License
This project is licensed under the MIT License.