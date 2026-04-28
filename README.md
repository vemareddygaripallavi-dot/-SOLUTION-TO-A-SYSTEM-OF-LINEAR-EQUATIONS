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
#Program to find the solution for the given linear equations.


#Developed by: Vemareddygari Pallavi


#RegisterNumber:212225230293


import numpy as np


matrixA=np.array([[1,3],[2,5]])


const=np.array([5,-3])


result=np.linalg.solve(matrixA,const)


print(result)
## Output:
<img width="1189" height="846" alt="image" src="https://github.com/user-attachments/assets/1a3ce794-d735-4005-8a64-e7d9593dc244" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

