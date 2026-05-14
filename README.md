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
```
#Program to find the solution for the given linear equations.
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[1,-3],[3,1]])
b=np.array([0,10])
x=np.linalg.solve(a,b)
print(x)

#Developed by:gowtham 
#RegisterNumber:212225040099
```

## Output:
<img width="1159" height="163" alt="Screenshot 2026-05-14 103352" src="https://github.com/user-attachments/assets/fe5e24e6-f4c4-4d93-8b52-8edd465aeaff" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

