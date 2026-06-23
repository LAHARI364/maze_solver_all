# Maze Solver and Generator

A Python project that generates random mazes and solves them using multiple pathfinding algorithms, including DFS, BFS, Dijkstra, and A* Search.

## About The Project


This project demonstrates both maze generation and maze-solving techniques using graph traversal and pathfinding algorithms.

<img width="1806" height="7026" alt="image" src="https://github.com/user-attachments/assets/d94bc9e1-6a7d-49e9-b351-f7328e956ac2" />


### Maze Generation

The maze is generated using the following steps:

1. Create a matrix filled with `0`s representing walls.
2. Generate a grid structure using `1`s to represent possible paths.
3. Apply Depth-First Search (DFS) to carve passages between cells.
4. Connect the cells to create a fully traversable maze.

### Maze Solving Algorithms

#### Depth-First Search (DFS)

DFS explores one path as deeply as possible before backtracking.

- Uses a stack data structure.
- Memory efficient.
- Does not always find the shortest path.

#### Breadth-First Search (BFS)

BFS explores neighboring nodes level by level.

- Uses a queue data structure.
- Guarantees the shortest path in an unweighted maze.
- May require more memory than DFS.

#### Dijkstra's Algorithm

Dijkstra's algorithm finds the shortest path by continuously selecting the node with the smallest known distance from the start.

- Guarantees the shortest path.
- Works well for weighted and unweighted graphs.
- Uses a greedy approach.

#### A* Search Algorithm

A* enhances Dijkstra's algorithm by using a heuristic function to estimate the distance to the goal.

- Faster than Dijkstra in most cases.
- Guarantees the shortest path with an admissible heuristic.
- Commonly used in games and navigation systems.

## Features

- Random maze generation
- Maze solving using:
  - DFS
  - BFS
  - Dijkstra
  - A*
- Visualization of generated mazes and solutions
- Easy-to-understand Python implementation

## Getting Started

### Prerequisites

Make sure Python is installed on your system.

Required packages:

```bash
pip install numpy
```

> Note: `random` and `time` are built-in Python modules and do not need to be installed separately.

### Installation

Clone the repository:

```bash
git clone https://github.com/LAHARI364/maze_solver_all.git
cd maze_solver_all
```

## Usage

Run the project:

```bash
python main.py
```

`main.py` is the entry point of the application.



## Future Improvements

- Add more maze generation algorithms
- Add weighted mazes
- Benchmark algorithm performance
- Interactive GUI visualization

## Author

Created by Lahari.

## License

This project is open source and available under the MIT License.
