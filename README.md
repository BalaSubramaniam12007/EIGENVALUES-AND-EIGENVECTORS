# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: BALASUBRMANIAM L
#RegisterNumber:24901213

import numpy as np

A = np.array([[2, -3, 0], [2, -5, 0], [0, 0, 3]])

eigenvalues, eigenvectors = np.linalg.eig(A)

print("Eigen values are", eigenvalues, "and Eigen Vectors are", eigenvectors)

```
## Output:
![image](https://github.com/user-attachments/assets/300e1200-90f0-462e-8793-de6abd3af3c6)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
