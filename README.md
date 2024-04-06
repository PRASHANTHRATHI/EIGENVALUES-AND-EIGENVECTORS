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
Prepare the lists from each equations and assign in np.array()
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program

## Program:
```
Program to find the eigen values and eigen vectors.
Developed by: Prashanth.K
RegisterNumber:212223230152

import numpy as np
A=np.array(([4,2],[2,4]))
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![Screenshot 2024-04-06 142955](https://github.com/PRASHANTHRATHI/EIGENVALUES-AND-EIGENVECTORS/assets/145743120/21753bb8-a67c-4aaf-a65c-3afe2c5c5eaa)
![Screenshot 2024-04-06 143011](https://github.com/PRASHANTHRATHI/EIGENVALUES-AND-EIGENVECTORS/assets/145743120/45bb6bda-35fb-470d-923b-e2238933da05)
![Screenshot 2024-04-06 143020](https://github.com/PRASHANTHRATHI/EIGENVALUES-AND-EIGENVECTORS/assets/145743120/85ca2f4b-94f0-470b-8dfd-c7002841958c)



## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
