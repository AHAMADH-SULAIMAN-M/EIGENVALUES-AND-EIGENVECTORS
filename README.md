# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step1 :Import the numpy module to use the built-in functions for calculation

### Step 2: Prepare the lists from the matrix and assign in np.array()

### Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: End the program.

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: AHAMADH SULAIMAN M
#RegisterNumber: 212224230009

import numpy as np
A = np.array([[6,2,3],[3,1,1],[10,3,4]])
AInverse = np.linalg.inv(A)
print(AInverse)


```
## Output:

<img width="1279" height="350" alt="image" src="https://github.com/user-attachments/assets/336cc3ac-47be-4dc1-9448-3ad25076b065" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
