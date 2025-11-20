# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors

## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation 
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Harikrishnan.S
#RegisterNumber:212224100020
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
eigen_values,eigen_vectors = np.linalg.eig(A)
print(f"Eigen values are {eigen_values} and Eigen Vectors are {eigen_vectors}")
```
## Output:
<img width="1342" height="875" alt="image" src="https://github.com/user-attachments/assets/d6c2811b-e24f-4bd5-bb25-4da9cc3561e0" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
