Here’s the updated README to reflect your specific maze patterns and algorithms:

---

# Pathfinding Visualizer

A web-based pathfinding visualizer that demonstrates the functionality of various pathfinding algorithms. This tool allows users to visualize how algorithms navigate through a grid to find the shortest path between two points. It also includes multiple maze patterns for creating custom environments, enabling deeper insights into how different algorithms perform.

## Features

- Visualizes popular pathfinding algorithms such as:
  - Dijkstra's Algorithm (Weighted)
  - A* Search (Weighted)
  - Greedy Best-First Search
  - Swarm Algorithm
  - Convergent Swarm Algorithm
  - Bidirectional Swarm Algorithm
  - Breadth-First Search (Unweighted)
  - Depth-First Search (Unweighted)
  
- Maze generation patterns:
  - Recursive Division
  - Recursive Division (Vertical Skew)
  - Recursive Division (Horizontal Skew)
  - Basic Random Maze
  - Basic Weight Maze
  - Simple Stair Pattern

- Interactive UI:
  - Set start and end points manually
  - Add or remove walls on the grid
  - Adjust grid size and speed of the visualization
  - Reset the grid and visualization
  - Toggle between different algorithms

## Table of Contents

1. [Demo](#demo)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Pathfinding Algorithms](#pathfinding-algorithms)
5. [Maze Patterns](#maze-patterns)
6. [Technologies Used](#technologies-used)
7. [Future Improvements](#future-improvements)
8. [License](#license)

## Demo

Try out the live demo: https://pathfindingviz.netlify.app/#

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/pathfinding-visualizer.git
    cd pathfinding-visualizer
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Start the development server:

    ```bash
    npm start
    ```

4. Open the app in your browser at `http://localhost:3000`

## Usage

1. Select a pathfinding algorithm from the dropdown menu.
2. Choose a maze generation pattern if you want to visualize the algorithms in a pre-made maze.
3. Set your start and end points by clicking on the grid.
4. Click and drag on the grid to create walls.
5. Press the "Visualize" button to see the algorithm in action.
6. Reset or adjust settings as needed.

## Pathfinding Algorithms

- **Dijkstra's Algorithm**: Guarantees the shortest path and works with weighted grids.
- **A* Search**: An informed search algorithm using heuristics to speed up the search, optimal and complete.
- **Greedy Best-First Search**: A faster algorithm, but does not guarantee the shortest path.
- **Swarm Algorithm**: A less optimal algorithm that mimics the behavior of a swarm. It balances between exploration and exploitation.
- **Convergent Swarm Algorithm**: A modified version of the Swarm Algorithm that converges towards the target faster.
- **Bidirectional Swarm Algorithm**: Similar to the Swarm Algorithm but expands from both start and end points.
- **Breadth-First Search (BFS)**: Explores all possible nodes layer by layer, guaranteeing the shortest path on unweighted grids.
- **Depth-First Search (DFS)**: Explores as far as possible along each branch before backtracking; may not find the shortest path.

## Maze Patterns

- **Recursive Division**: A divide-and-conquer approach to generating mazes.
- **Recursive Division (Vertical Skew)**: A variation of Recursive Division with a vertical skew in the wall placements.
- **Recursive Division (Horizontal Skew)**: A variation of Recursive Division with a horizontal skew in the wall placements.
- **Basic Random Maze**: Walls are placed randomly throughout the grid.
- **Basic Weight Maze**: A grid with random weighted cells instead of walls.
- **Simple Stair Pattern**: A simple stair-like structure of walls.

## Technologies Used

- **Frontend**:
  - React.js
  - CSS for grid and visual elements
  - HTML5 for structure

- **Algorithms**:
  - JavaScript implementations of pathfinding and maze generation algorithms

## Future Improvements

- Add additional algorithms (e.g., Jump Point Search)
- Improve maze generation techniques for more complex patterns
- Allow users to save and share their grid configurations
- Add a step-by-step mode for better algorithm understanding
- Optimize algorithm performance for larger grids

