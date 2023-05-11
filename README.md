# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from the matrix and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Naveen Raja N.R
#RegisterNumber:212222230093
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
evalues,evector=np.linalg.eig(A)
print("Eigen values are {0} and Eigen Vectors are {1}".format(evalues,evector))
```

## Output:
![maths for ai exp 4](https://github.com/naveenraja2004/EIGENVALUES-AND-EIGENVECTORS/assets/118707204/c55260cd-5599-444d-a698-b0ec1b6fc6d1)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
