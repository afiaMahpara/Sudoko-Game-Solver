# Sudoko-Game-Solver
This project demonstrates how AI techniques like CSP and heuristics (MRV) can efficiently solve constraint-based problems like Sudoku.
#  Sudoku Solver & Generator (CSP + MRV)

This project is a Python-based Sudoku Solver and Generator that uses Artificial Intelligence techniques like **Constraint Satisfaction Problem (CSP)**, **Backtracking**, **Minimum Remaining Values (MRV)**, and **Forward Checking**.

---

##  Features

-  Generates Sudoku puzzles with different difficulty levels  
-  Solves Sudoku using AI techniques  
-  Manual play mode for users  
-  Hint system for assistance  
-  Color-coded output:
  -  Original values  
  -  Correct inputs  
  -  Incorrect inputs  

---

##  Algorithms Used

- **Backtracking Search**
- **Constraint Satisfaction Problem (CSP)**
- **MRV (Minimum Remaining Values)**
- **Forward Checking**

---

##  How It Works

1. A complete valid Sudoku board is generated using backtracking.
2. Numbers are removed based on difficulty level.
3. User can:
   - Solve manually
   - Let AI solve automatically

---

##  Requirements

- Python 3.x

No external libraries required.

---

##  How to Run

```bash
python sudoku.py
