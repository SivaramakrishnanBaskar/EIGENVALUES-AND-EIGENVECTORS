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

## Question:
![Ex4ques'](https://user-images.githubusercontent.com/119476322/229544988-25654449-0285-43a1-b07e-843ea54414ff.png)

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

## Output:
![rEC 4 out](https://user-images.githubusercontent.com/119476322/229545449-be17d01a-8d47-4b8d-9cbd-c9edb27dbf6e.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
