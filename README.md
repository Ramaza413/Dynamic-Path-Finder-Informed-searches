 Dynamic Pathfinding
 Overview

This project implements a dynamic pathfinding visualizer that demonstrates A* and Greedy search algorithms in a grid environment 
with real-time dynamic obstacles. The agent moves step by step from
start node to a goal node while obstacles may randomly appear, forcing the algorithm to adapt and replan.

The project includes:
A* and Greedy Best-First Search algorithms.
Manhattan and Euclidean heuristics.
A grid visualizer using `matplotlib` that shows:
  * Explored nodes
  * Current frontier
  * Path taken
  * Dynamic obstacles
Features
  Dynamic Obstacles: Obstacles can appear randomly during execution, simulating real-world dynamic environments.
  Real-Time Replanning: The algorithm continuously adapts to changes in the grid while moving toward the goal.
  Step-by-Step Visualization:Shows the progression of search, frontier expansion, and final path.
  User-Configurable Options:
   Algorithm selection: A* or Greedy
   Heuristic: Manhattan or Euclidean
   Scenario: Best case (sparse obstacles) or worst case (dense obstacles
 The visualizer window will open, showing the grid with:
     Blue: Start node (S)
     Dark Green: Goal node (G)
     Red: Obstacles
     Orange: Frontier nodes
     Light Blue: Explored nodes
     Green: Path taken
 The search will execute step by step, updating dynamically if obstacles appear in the planned path.

4. Once the goal is reached or no path is found, metrics are displayed.

o that?
