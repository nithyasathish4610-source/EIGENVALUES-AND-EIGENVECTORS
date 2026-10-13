# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : start the program
### Step 2: import the numpy library and create the given matrix using np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: display the eigen values and eigen vectors and stop the program

## Program:
### Program to find the eigen values and eigen vectors.
### Developed by:Nithya sri.s 
### RegisterNumber:26010142
### import os
### os.environ["OPENBLAS_NUM_THREADS"]="1"
### import numpy as np
### a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
### values,Vectors=np.linalg.eig(a)
### print("Eigen values are {} and Eigen Vectors are {}".format(values,Vectors))

## Output:
<img width="1122" height="653" alt="image" src="https://github.com/user-attachments/assets/d95730eb-e7c3-4c39-ac2b-6da1b549d796" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
