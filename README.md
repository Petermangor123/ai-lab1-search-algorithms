# AI Search Algorithms Lab

This repository contains my implementation of search algorithms for an Artificial Intelligence course. The lab explores both uninformed and informed search strategies applied to grid-based pathfinding problems.

## Overview

The project implements and compares multiple search algorithms on grid maps featuring:
- Obstacles that block movement
- Weighted terrain costs that affect path cost
- Visualisation of solution paths

## Algorithms Implemented

### Uninformed Search (Lab 1A)
- **Breadth-First Search (BFS)**: Explores all nodes at the current depth before moving deeper
- **Depth-First Search (DFS)**: Explores as far as possible along each branch before backtracking
- **Uniform Cost Search (UCS)**: Finds the lowest-cost path by expanding nodes in order of path cost

### Informed Search (Lab 1B)
- **Greedy Best-First Search**: Prioritises nodes closest to the goal using a heuristic
- **A* Search**: Balances path cost and heuristic estimate for optimal solutions
- **Weighted A* Search**: Trades optimality for speed by overweighting the heuristic
- **IDA* (Bonus)**: Memory-efficient iterative deepening version of A*

## Key Features

- Grid-based map representation with obstacles
- Weighted terrain costs for realistic path planning
- Manhattan and Euclidean distance heuristics
- Path visualisation with matplotlib
- Performance comparison across algorithms (nodes expanded, solution cost, frontier size)

## Results

The experiments demonstrate trade-offs between:
- **Solution optimality** (A* and UCS find optimal paths)
- **Search speed** (Greedy and Weighted A* expand fewer nodes)
- **Path cost** (Greedy can find expensive paths despite shorter distances)
- **Memory usage** (IDA* uses less memory than A*)

## How to Run

1. Clone this repository
2. Install required packages: `pip install numpy pandas matplotlib`
3. Open the notebooks in Jupyter Notebook or VS Code
4. Run all cells to reproduce the results

## Repository Structure
