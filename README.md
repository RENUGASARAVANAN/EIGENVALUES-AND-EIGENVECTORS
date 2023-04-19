# EIGENVALUES-AND-EIGENVECTORS

## Aim:

To write a python program to find the Eigenvalues and Eigen Vectors

## Equipment’s required:

1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:


### Step1 :
To write a python program to find the Eigenvalues and Eigen Vectors
 

### Step 2:
Get the input

### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: 
End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:Renuga.S
#Registernumber:212222230118
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
evalues,evector=np.linalg.eig(A)
print("Eigen values are",evalues,"and Eigen Vectors are",evector)
```

## Output:
![S RENUGA EIGEN VALUES](https://user-images.githubusercontent.com/119292258/227716393-7fd0ef44-9a87-4ea1-a086-c2f692c6764b.png)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
