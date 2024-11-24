# CI2024_lab3: N-Puzzle Solver

This project implements the **A*** algorith for solving the N-Puzzle problem. The algorithm is tested on puzzles of various dimensions (3x3, 4x4, and 5x5), analyzing its performance in terms of **solution quality** and **computational cost**.

## Key Features
- **A***: Combines path cost and Manhattan distance for optimal solutions.
- Automated experiments: Generate random puzzles and analyze algorithm performance.

## Experiment Results
### 3x3 Puzzle
- **Average solution length**: 22.05 moves
- **Average cost**: 871.15 nodes evaluated
- **Efficiency**:  0.025

### 4x4 Puzzle
- **Average solution length**: 49.80 moves
- **Average cost**: 2,759,096.00 nodes evaluated
- **Efficiency**:  0.000018

### 5x5 Puzzle
The 5x5 puzzle proved significantly more computationally expensive, with no solution found within a two-hour runtime.

## Observations
- Solving a **3x3 puzzle** is quick and efficient for both algorithms.
- For a **4x4 puzzle**, A* provides solutions, but at a significantly higher computational cost.
- The efficiency in solving the 3x3 is much higher.