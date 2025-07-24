# 🧩 Sudoku Solver in Java

A simple yet efficient **Java-based Sudoku Solver** using **backtracking algorithm**. This project reads a Sudoku puzzle, solves it, and prints the solution on the console.

---

## 📌 Project Overview

This project is a command-line based Sudoku solver. It reads a predefined 9x9 Sudoku grid (with empty cells as `0`), applies a recursive backtracking algorithm, and prints the solved board.

The key logic is implemented in the `Sudoku` class, and the program is launched from `App.java`.

---

## 🛠️ Technologies Used

- Java (JDK 8 or above)
- OOP Concepts
- Recursion
- Backtracking Algorithm
- Command Line / Console Output

---

## 🚀 Features

- Takes a 9x9 Sudoku grid as input.
- Uses backtracking to fill all empty cells.
- Validates number placement using Sudoku rules.
- Displays the original and solved grid in the console.

---

## 💡 How It Works

1. **Grid Representation**:  
   A 2D `int[][]` array represents the Sudoku board, where empty cells are marked with `0`.

2. **Backtracking**:  
   The algorithm finds the first empty cell and tries numbers from 1–9. If a number is valid (row, column, subgrid), it's placed, and recursion continues. If not solvable, it backtracks.

3. **Validation Function**:  
   Checks for safe number placement in rows, columns, and 3x3 subgrids.

4. **Solution Output**:  
   Once solved, the board is printed neatly to the console.

---

## 🧠 What I Did / What I Learned

- Designed the algorithm using **recursive backtracking**.
- Practiced **Java OOP principles** by separating concerns into `App` and `Sudoku` classes.
- Learned how to validate Sudoku rules programmatically.
- Improved my **problem-solving** and **debugging** skills through recursion and base case handling.
- Understood how to represent grid-based puzzles in arrays.

---

## 📁 File Structure

├── App.java # Main method to run the Sudoku solver
├── Sudoku.java # Contains the logic to solve Sudoku using backtracking


---

## ▶️ How to Run the Program

### Prerequisites:
- Java installed (JDK 8+)
- IDE or terminal to run `.java` files

### Sample Output Image is Uploaded
