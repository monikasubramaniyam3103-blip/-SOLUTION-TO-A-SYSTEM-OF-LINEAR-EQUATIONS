# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
import numpy as np

# Coefficient matrix
A = np.array([[1, -3],
              [3,  1]])

# Constant matrix
B = np.array([0, 10])

# Solve the system
solution = np.linalg.solve(A, B)

# Print in expected format
print(solution)


## Output:
<img width="1255" height="744" alt="Screenshot 2026-02-05 134106" src="https://github.com/user-attachments/assets/1d8578e4-25bc-41ea-ab57-6b1ebc4af79e" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

