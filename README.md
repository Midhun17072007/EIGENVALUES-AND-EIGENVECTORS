# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the numpy module to use the built-in functions for calculations.

### Step 2:
Prepare the lists from each equations and assign in np.array()

#### Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4:
END OF PROGRAM
## Program:
~~~
#Program to find the eigen values and eigen vectors.
#Developed by: MIDHUN S
#RegisterNumber:212224230158

import numpy as np
a= np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))
~~~
## Output:
![Screenshot 2025-04-26 111001](https://github.com/user-attachments/assets/ef8800a0-bd8f-4f42-8b4e-a7b758475fa2)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
