# Search-Algorithms-AI-Star-Puzzle-Solver


This repository contains a Python Jupyter Notebook implementation for solving the Star Puzzle, a grid-based puzzle where the challenge is to arrange the first twelve positive numbers on a STAR-shaped grid, satisfying specific sum conditions.

## Project Description

The Star Puzzle is modeled as a state space problem, and the implementation utilizes the AIMA-Python code repository, which includes search algorithms covered in the book "Artificial Intelligence: A Modern Approach." The tasks involve designing a state representation, defining a `StarPuzzle` class, creating problem instances of varying complexity, solving puzzles using Breadth-First Search and A* search algorithms, and reporting summary statistics.

## Project Structure

- **[StarPuzzle.ipynb](StarPuzzle.ipynb):** Jupyter Notebook containing the implementation and documentation.
- **[AIMA-Python](https://github.com/aimacode/aima-python):** A submodule linked to the AIMA-Python code repository.
- **[examples](examples):** Directory containing example StarPuzzle instances.
- **[images](images):** Directory containing images used in the documentation.

## How to Use

1. Open the Jupyter Notebook `StarPuzzle.ipynb` using Jupyter Notebook or Jupyter Lab.
2. Follow the instructions and explanations within the notebook to understand the implementation and run the examples.
3. Ensure you have the required dependencies installed (AIMA-Python library).

## Examples

The `examples` directory contains four problem instances of the StarPuzzle with varying levels of complexity. Each instance involves different initial states, and the `StarPuzzle` class is applied to find the solutions.

## Running Search Algorithms

- **Breadth-First Search:** Use the provided code cell to apply Breadth-First Search and print each state of the solution path.
- **A* Search:** Another code cell is available to solve the StarPuzzle using A* search and display the solution path.

## Heuristic Explanation

In exercise 5, an appropriate heuristic for the StarPuzzle is defined and explained in a markdown cell. The heuristic is designed to be admissible, and examples are provided to illustrate its application.

## Summary Statistics

In exercise 7, the notebook reports summary statistics for Breadth-First Search and A* applied to different StarPuzzle instances. The impact of the heuristic function defined in exercise 5 on reducing the number of explored nodes by the A* algorithm is explained.

