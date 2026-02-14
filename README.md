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
```
#Program to find the eigen values and eigen vectors.
#Developed by: Vishwa.s
#RegisterNumber:225012636
import numpy as np
a=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
<img width="956" height="571" alt="image" src="https://github.com/user-attachments/assets/6327a3d4-d8fa-4568-857e-665154157755" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
