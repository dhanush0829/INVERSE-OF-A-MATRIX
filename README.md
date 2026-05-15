# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### step2 : Prepare the lists from each linear equations and assign in np.array() 
### Step 3: Using the np.linalg.solve(), we can find the solutions.
### Step 4: end the program

## Program:
```py
#Program to find the inverse of a matrix.
#Developed by: Dhanush M
#RegisterNumber:212225230051
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[6,2,3],[3,1,1],[10,3,4]])
b=np.linalg.inv(a)
print(b)

```
## Output:
<img width="807" height="707" alt="image" src="https://github.com/user-attachments/assets/69150acb-8510-4ed4-8f94-3f609f8a9b8d" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

