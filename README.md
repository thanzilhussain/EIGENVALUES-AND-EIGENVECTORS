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
Prepare the lists from each linear equations and assign in np.array()

### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program

## Program:

#Program to find the eigen values and eigen vectors.

#Developed by: THANZIL HUSSAIN A

#RegisterNumber:25018773
```py
import numpy as np
matrix=np.array([[2,2],[1,3]])
eig_values,eig_vectors=np.linalg.eig(matrix)
print(f"Eigen values are {eig_values} and Eigen Vectors are {eig_vectors}")
```
## Output:

<img width="1197" height="725" alt="image" src="https://github.com/user-attachments/assets/4ad07ef4-aba7-45da-b4b2-35258b7304a6" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
