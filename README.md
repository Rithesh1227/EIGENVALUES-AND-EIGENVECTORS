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
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Rithesh S
#RegisterNumber: 212225220084
import numpy as np
a=np.array([[2,2],[1,3]])
x,y=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(x,y))
```
## Output:
<img width="1232" height="198" alt="image" src="https://github.com/user-attachments/assets/6046bd0f-d4b4-4dac-ae5c-2b7135f4b1bc" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
