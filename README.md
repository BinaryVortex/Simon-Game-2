# Simon Game

A simple Simon memory game built with vanilla HTML, CSS, and JavaScript.

![Screenshot of Simon Game](./Screenshot%202024-08-29%20080714.png)

Table of contents
- About
- Demo
- How to play
- Controls
- Project structure
- Installation
- Contributing
- License & Credits

About

This is a lightweight implementation of the classic Simon memory game. The game plays an expanding sequence of colored tiles (with associated sounds) and the player must repeat the sequence correctly. It’s implemented using only HTML, CSS and plain JavaScript so it’s easy to read and modify.

Demo

Open index.html in a web browser to play locally, or host the repository with GitHub Pages (see Installation).

How to play

1. Press the Start button to begin a new game.
2. Watch the sequence of tiles that light up and play sounds.
3. Repeat the sequence by clicking/tapping the tiles in the same order.
4. If you repeat the sequence correctly, the round increases and a new color is added.
5. If you make a mistake, the game ends — press Start to try again.

Controls

- Click/tap the colored tiles to input the sequence.
- Use the Start button to begin a new game.

Project structure

- index.html — main HTML file containing the game layout and UI.
- style.css — styles for layout, colors, and animations.
- script.js — game logic and event handlers.
- Screenshot 2024-08-29 080714.png — screenshot used in this README.

Installation

To run locally:

1. Clone the repository:

   git clone https://github.com/BinaryVortex/Simon-Game-2.git

2. Open index.html in your preferred web browser (double-click or open via File -> Open).

Optional: Use a simple local server for a better development experience (recommended if testing audio behavior):

- Python 3: `python -m http.server 8000` then open http://localhost:8000
- VS Code: Use the Live Server extension and open the repository folder.

Contributing

Improvements, bug fixes, and pull requests are welcome. If you plan to contribute:

1. Fork the repository.
2. Create a feature branch for your changes.
3. Submit a pull request describing your changes.

Notes and ideas for improvements
- Add strict/strict-mode options and difficulty settings.
- Add high score tracking using localStorage.
- Make the game responsive for small screens and touch-only devices.
- Add accessible keyboard controls and ARIA attributes.

License & Credits

This repository does not include a license file. If you want to allow others to reuse or contribute under a specific license, add a LICENSE file (for example MIT).

Author

BinaryVortex — https://github.com/BinaryVortex
