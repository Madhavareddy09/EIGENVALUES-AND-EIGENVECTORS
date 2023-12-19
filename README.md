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
Prepare the lists from each linear equations and assign in np.array().
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program.
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Kamireddy Madhava reddy
#RegisterNumber: 23009929
import numpy as np
A = np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors = np.linalg.eig(A)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```
## Output:
![image](https://github.com/Madhavareddy09/EIGENVALUES-AND-EIGENVECTORS/assets/145742470/4e279ea6-9fde-4a68-8532-73221f69c2af)



## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
