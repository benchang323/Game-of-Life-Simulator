# Game-of-Life Simulator

## Overview
This MATLAB project replicates Conway’s Game of Life. It encompasses the creation of a Graphical User Interface (GUI) for easy simulation of the cellular automaton. The GUI allows for the importation of RLE files, creation of random matrices (Soup), and offers various functionalities to control the simulation of the Game of Life.

## Features
- Import RLE files and create random matrices (Soup).
- Load and clear simulations.
- Step through generations of the simulation.
- Play simulation at a specified frame rate.
- Define the number of generations to run.
- Export frames and movies of the simulation.
- Ability to export RLE at any given frame.
- Move backward in a simulation.
- Change boundary conditions.
- Dynamic resizing of the simulation grid.

## Files
- `GOL.m`: Implements the Game of Life, a classic cellular automaton.
- `program_guiprob.m`: Provides a graphical user interface for solving problems or visualizing patterns.
- `RLE_decoder.m`: Decodes RLE encoded patterns for cellular automata simulations.

## Tech Stack
- MATLAB

## Libraries/Dependencies
- MATLAB Runtime

## Installation
Clone the repository to your local machine:
```
git clone https://github.com/benchang323/Game-of-Life-Simulator
cd Game-of-Life-Simulator
```

## Usage & Examples
To operate the GUI, run `program_guiprob.m`. The GUI window will provide all the necessary controls for importing RLEs, creating Soups, controlling the simulation, and exporting results.

### Inputs
- Use the provided buttons to import RLEs or create a Soup.

### Running
- Control the simulation using the GUI buttons and menus to step through generations or play the simulation.

### Exporting
- Frames and movies can be exported using the GUI controls, providing a name for the files when prompted.
