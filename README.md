# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Write a python program for the given matrix
### Step 2: Using numpy library
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Run the program and get the output

## Program:
```
import numpy as np
a= np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))
```
## Output:
<img width="1272" height="170" alt="Screenshot 2026-03-20 224835" src="https://github.com/user-attachments/assets/f79da57b-90c8-4daa-a534-b0ec1687ad3e" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
