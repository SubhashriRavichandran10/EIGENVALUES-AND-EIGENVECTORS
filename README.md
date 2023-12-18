# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 

Start the program.

### Step 2: 

prepare the lists from the each inverseof a matrix and design in ip.array().

### Step 3:'

Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: 

End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:R.Subhashri 
#RegisterNumber:23012776
import numpy as np
A=[[2,2],[1,3]]
values,vectors=np.linalg.eig(A)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```

## Output:
![Screenshot 2023-12-18 232217](https://github.com/SubhashriRavichandran10/EIGENVALUES-AND-EIGENVECTORS/assets/145743413/7901919c-c627-4f91-a9be-fd762d85d536)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
