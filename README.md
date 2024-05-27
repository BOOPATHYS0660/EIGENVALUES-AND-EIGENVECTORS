# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare the lists from each equations and assign in np.array()
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program
## Program:
```
#Program to find the eigenvalues and associated eigenvectors for the matrix
#Developed by:Boopathy S
#RegisterNumber:2305003002
import numpy as np
A=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(A)
print(f"Eigen values are {values} Eigen vectors are {vectors}")
```
## Output:
![Screenshot 2024-05-27 142016](https://github.com/BOOPATHYS0660/EIGENVALUES-AND-EIGENVECTORS/assets/155909381/1f299740-eb3e-41ad-bf4e-e257c5fa611a)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
