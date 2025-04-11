# Skyscraper_4x4

**Task : 4x4 Grid Puzzle Solver**


This repository contains the Python implementation for the task. It involves solving a 4x4 grid puzzle (a skyscraper puzzle variant) where each cell represents a tower height (1 to 4), and clues indicate the number of visible towers from each direction. The solver uses a constraint propagation approach to deduce the grid configuration.

## Task Description

The goal is to fill a 4x4 grid such that:
- Each row and column contains the numbers 1 to 4 exactly once.
- Numbers represent tower heights.
- Clues outside the grid (top, bottom, left, right) indicate how many towers are visible from that direction, with higher towers blocking lower ones.
- The solution iteratively applies rules to narrow down possible values for each cell.

The task requires implementing functions (A to L) to initialize the grid, apply constraints, and solve four specific puzzle configurations.

## Prerequisites

- Python 3.x
- NumPy library (`pip install numpy`)

The code uses only the allowed Python commands and NumPy functions specified (`numpy.zeros`, `numpy.empty`).

## Usage

1. **Clone the repository**:
   ```bash
   git clone https://github.com/nakshatraaditya/Skyscraper_4x4
