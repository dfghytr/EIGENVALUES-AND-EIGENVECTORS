# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the numpy module to use the built-in function for calculation.

### Step 2:
prepare the listfrom each linear equation and assign in np.array()

### Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4:
End the program.
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Abdul kalaam k m
#RegisterNumber:23005114
import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {} ".format(values,vectors))
```

## Output:
![Screenshot 2023-12-29 154447](https://github.com/dfghytr/EIGENVALUES-AND-EIGENVECTORS/assets/138970628/c58f0e33-c40b-47f0-a45b-b43adef37ea4)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
