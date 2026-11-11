# Conway-s-Game-of-Life
🧬 Conway's Game of Life

A Python implementation of John Conway's famous cellular automaton, Game of Life. Watch fascinating patterns evolve, stabilize, or disappear based on a simple set of deterministic mathematical rules!

🌟 Overview

The Game of Life is a zero-player game, meaning its evolution is determined purely by its initial state. You create an initial configuration of cells and observe how they evolve over time.

📜 The Rules of Life

Underpopulation: Any live cell with fewer than two live neighbours dies.

Survival: Any live cell with two or three live neighbours lives on to the next generation.

Overpopulation: Any live cell with more than three live neighbours dies.

Reproduction: Any dead cell with exactly three live neighbours becomes a live cell.

✨ Features

🔄 Real-Time Simulation: Smooth grid rendering showing generations evolving in real-time.

🎨 Interactive Controls: Pause, step through frames, play, and clear the grid.

✏️ Custom Initial States: Click on cells during pause mode to toggle them ON/OFF and draw custom patterns (Gliders, Oscillators, Spaceships).

🔀 Random Seed Generator: Start instantly with a randomly populated grid.

⏱️ Speed Control: Adjustable simulation speed (FPS / tick rate).

🛠️ Built With

Python 3.x - Core cellular automata logic and grid updates.

Pygame / Tkinter - Visual grid rendering and interactive mouse/keyboard controls.

🚀 Getting Started

Prerequisites

Ensure you have Python 3 installed. If using Pygame for rendering, install it via terminal:

pip install pygame


Installation & Running

Clone the repository:

git clone https://github.com/YOUR-USERNAME/Conways-Game-Of-Life.git
cd Conways-Game-Of-Life


Run the simulation:

python main.py


(Replace main.py with your Python entry script name if it is different).

🕹️ Controls

Left Click: Toggle cell state (Alive / Dead) during pause.

Spacebar: Pause / Resume the simulation.

C: Clear the grid.

R: Generate a random grid pattern.

Up / Down Arrows: Increase / Decrease simulation speed.

🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.
