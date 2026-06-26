# Sudoku Solver

A Python-based Sudoku Solver implemented in a Jupyter Notebook using the **Backtracking Algorithm**. The project demonstrates how recursion and constraint checking can efficiently solve Sudoku puzzles by filling empty cells while satisfying all game rules.

---

## Features

- Solves standard 9×9 Sudoku puzzles
- Implements the Backtracking Algorithm
- Validates row, column, and 3×3 subgrid constraints
- Recursive approach for efficient puzzle solving
- Easy-to-understand implementation in a Jupyter Notebook

---

## Technologies Used

- Python
- Jupyter Notebook

---

## Algorithm

The solver uses the **Backtracking Algorithm**, which works as follows:

1. Find an empty cell in the Sudoku grid.
2. Try numbers from 1 to 9.
3. Check whether the chosen number is valid according to Sudoku rules.
4. If valid, place the number and recursively solve the remaining puzzle.
5. If no valid number exists, backtrack and try another possibility.
6. Continue until the puzzle is completely solved.

---

## Project Structure

```
Sudoku-main/
│
├── Sudoku.ipynb
└── README.md
```

---

## How to Run

1. Clone the repository.

```bash
git clone https://github.com/Swaroop-Haridas/Sudoku.git
```

2. Navigate to the project directory.

```bash
cd Sudoku
```

3. Open the notebook.

```bash
jupyter notebook Sudoku.ipynb
```

or

```bash
jupyter lab
```

4. Run all cells to solve the Sudoku puzzle.

---

## Example Workflow

- Input an unsolved Sudoku grid.
- The algorithm searches for empty cells.
- Valid numbers are placed recursively.
- Backtracking occurs whenever a conflict is found.
- The completed Sudoku grid is displayed.

---

## Learning Outcomes

This project demonstrates:

- Recursive programming
- Backtracking algorithms
- Constraint satisfaction problems
- Problem-solving using Python
- Sudoku puzzle validation

---
## License

This project is intended for educational and learning purposes.
