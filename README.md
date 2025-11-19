# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from the matrix and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: SHANKAR SB
#RegisterNumber: 25017085
import numpy as np
A = np.array([[2, 2],[1, 3]])
eigenvalues, eigenvectors = np.linalg.eig(A)
print("Eigen values are", eigenvalues,"and Eigen Vectors are",eigenvectors)


```

## Output:
<img width="1340" height="843" alt="Screenshot 2025-11-19 112715" src="https://github.com/user-attachments/assets/be632fd2-8031-4721-9b2a-bd4084b4a5fb" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
