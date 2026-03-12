<h1 align="center">Sudoku Solver 🧩</h1>

<p align="center">
A C++ program that solves a 9×9 Sudoku puzzle using the Backtracking algorithm.
</p>

---

## 📌 Description
This project implements a **Sudoku Solver in C++** that automatically solves a standard **9×9 Sudoku puzzle**.

The program:
- Reads Sudoku input from the user or from a file
- Uses **Backtracking and Recursion**
- Fills the missing values while respecting Sudoku constraints

---

## ⚙️ Algorithm Used
The solver uses the **Backtracking Algorithm**:

1. Find an empty cell in the Sudoku grid.
2. Try placing numbers **1–9**.
3. Check if the number is valid in:
   - Row
   - Column
   - 3×3 subgrid
4. If valid, move to the next empty cell.
5. If not valid, **backtrack** and try another number.

---

## 📂 Project Structure
