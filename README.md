# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to access numerical operations and linear algebra tools.
### Step 2: 
Define the coefficient matrix A and the constant matrix B using np.array()
### Step 3: 
Use np.linalg.solve(A, B) to compute the solution vector.
### Step 4: 
Display the solution, showing the values of the unknown variables.
### Step 5:
Terminate the program.
## Program:
```Python
#Program to find the solution for the given linear equations.
#Developed by: HARIHARAN M
#RegisterNumber: 24900770

import numpy as np
a=[[1,-3],[3,1]]
b=np.array([0,10])
print(np.linalg.solve(a,b))
```
## Output:
![exma1](https://github.com/user-attachments/assets/6a106a9d-6e95-44e0-a82f-9597e6d4050f)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

