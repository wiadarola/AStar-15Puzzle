# 15-Puzzle Solver using A* Search

An artificial intelligence project that efficiently solves the 15-puzzle using the A* search algorithm.

## Table of Contents
- [Overview](#overview)
- [Algorithm](#algorithm)
- [Installation](#installation)
- [Usage](#usage)

## Overview

The 15-puzzle, also known as sliding tile puzzle, is a classic problem in the world of AI. This project aims to solve the 15-puzzle using the A* search algorithm, which is known for its efficiency in pathfinding and graph traversal.

## Algorithm

The A* search algorithm is employed to find the optimal path to solve the puzzle. It uses heuristics to prioritize its search towards the goal, ensuring efficient solutions even for more complex board configurations.

## Installation

1. Clone this repository: 
```
git clone https://github.com/wiadarola/15-puzzle-solver.git
```

2. Navigate to the directory:
```
cd 15-puzzle-solver
```

## Usage

To solve a 15-puzzle, provide a text file with the puzzle configuration and run the `15puzzle.py` script:

```
python 15puzzle.py path_to_input_file.txt
```
