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
#Developed by: GOKULAN S
#RegisterNumber: 25018529

import numpy as np
A=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
<img width="1252" height="688" alt="Screenshot 2026-02-12 223237" src="https://github.com/user-attachments/assets/179104fa-f136-46bf-938d-bb9fc2d80ea4" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
