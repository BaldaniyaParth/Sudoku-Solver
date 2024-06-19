# Sudoku Solver in C

Welcome to the Sudoku Solver project! This repository contains a C program that solves a given Sudoku puzzle using a backtracking algorithm.


### Features

- Solves any 9x9 Sudoku puzzle
- Uses a backtracking algorithm
- Prints the puzzle in a readable format


### Usage

1. Clone the repository:
```bash
    git clone https://github.com/yourusername/sudoku-solver.git
```

2. Navigate to the project directory:
```bash
    cd sudoku-solver
```

3. Compile the program:
```bash
    gcc -o sudoku_solver sudoku_solver.c
```

4. Run the program:
```bash
    ./sudoku_solver
```


### Code Overview

The main components of the program are:

- print_puzzle: Function to print the Sudoku puzzle in a readable format.
- valid_move: Function to check if a move is valid according to Sudoku rules.
- solve_puzzle: Function that uses backtracking to solve the puzzle.


### How to Run

1. Ensure you have a C compiler installed (e.g., GCC).
2. Compile the program using the provided command.
3. Execute the compiled program to see the original and solved puzzles.


### Contribution

Contributions are welcome! Please fork the repository and submit a pull request.