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
#Program to find the eigen values and eigen vectors.
#Developed by: 
#RegisterNumber:

import numpy as np
A = np.array([[4,2],[2,4]])
eigen_values,eigen_vectors = np.linalg.eig(A)
print(f"Eigen values are {eigen_values} and Eigen Vectors are {eigen_vectors}")


```
## Output:

<img width="1280" height="336" alt="image" src="https://github.com/user-attachments/assets/819b2989-5b48-4d8b-bcb1-4cb7edaeaa5e" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
