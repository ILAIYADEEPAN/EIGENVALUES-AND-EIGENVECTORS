# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 

first import numpy function in the pyhon porgramming.

### Step 2: 

Then next give the vlues for the given variables.

### Step 3: 

Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4:

Then run the program with to find the eigen values and eigen vectors.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: ILAIYADEEPAN.K
#RegisterNumber:23013535
import numpy as np
A=[[2,-3,0],[2,-5,0],[0,0,3]]
values,vectors=np.linalg.eig(A)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```

## Output:
![image](https://github.com/ILAIYADEEPAN/EIGENVALUES-AND-EIGENVECTORS/assets/147473334/25e070a8-7e6d-4489-b047-43a54c1ad57f)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
