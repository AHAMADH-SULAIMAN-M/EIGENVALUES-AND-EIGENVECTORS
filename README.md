# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step1 : Importing numpy library.
### Step 2: Defining the matrix using np.array()
### Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the eigen values and eigen vectors

## Program:

```
#Program to find the eigen values and eigen vectors.
#Developed by: AHAMADH SULAIMAN M
#RegisterNumber: 212224230009

import numpy as np
A = np.array([[4,2],[2,4]])
eigen_values,eigen_vectors = np.linalg.eig(A)
print(f"Eigen values are {eigen_values} and Eigen Vectors are {eigen_vectors}")
```

## Output:

<img width="1310" height="902" alt="image" src="https://github.com/user-attachments/assets/ede89b7c-44dd-4317-b54b-f4874c14376c" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
