# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import numpy as np
### Step 2: 
assing in np.array()in vector and value
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
end the program
## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: Dhanashree. M
#RegisterNumber:21005794
import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vector=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vector))

## Output:
![Annotation 2021-12-19 222950](https://user-images.githubusercontent.com/94165415/146787899-55431864-8397-4d34-90b2-691a38a68327.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
