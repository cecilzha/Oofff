# YApocalypse

This is a collaborative class project to create an interactive mini game of navigating a post-apocalyptic themed Yangon Academy. The game is originally written in Python and uses the Pygame library. The program is converted to a WASM file using Pygbag to run on a web browser. Check out web version of the game [here](https://cecilzha.github.io/yapocalypse).

## For Developers

The original Python code is available on the `main` branch. The `web` branch contains the web version of the game.

### Running the Game Using Pygbag

1. Install Pygbag using pip:
```bash
pip install pygbag
```

2. Run the following command to convert the Python code to a WASM file:
```bash
pygbag main.py
```

3. Open the `index.html` file in a web browser to play the game or follow the instructions on terminal.

### Running the Game Using Python

1. Install Pygame using pip:
```bash
pip install pygame
```

2. Run the following command to run the game:
```bash
python main.py
```

## Common Issues

- Cannot pip install pybag on macOS 10.15.7 (19H2026) https://github.com/pygame-web/pygbag/discussions/132

## Useful Links

- Pygame Documentation: https://www.pygame.org/docs/
- Pygbag Documentation: https://pygame-web.github.io/wiki/pygbag/

