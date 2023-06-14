# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
## Step1 : Import numpy library as np.

## Step 2: Create a matrix using array() function.

## Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

## Step 4: Get the output and end the program.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Sivaramakrishnan B
#RegisterNumber: 212222110044
import numpy as np
a= np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Program Statement:
![image](https://github.com/SivaramakrishnanBaskar/EIGENVALUES-AND-EIGENVECTORS/assets/119476322/ba42842c-7e97-4d8e-9417-a1534bd217a1)

## Output:
![image](https://github.com/SivaramakrishnanBaskar/EIGENVALUES-AND-EIGENVECTORS/assets/119476322/2a1e6de5-a89c-4bda-975c-223f1e3d0911)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
