# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program


## Program:

```
#Program to find the eigen values and eigen vectors.
#Developed by: G.Ramanujam
#RegisterNumber:212224240129
import numpy as np
A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
Values,Vectors=np.linalg.eig(A)
print(f"Eigen values are {Values} and Eigen Vectors are {Vectors}")
```

## Output:

<img width="1247" height="223" alt="Screenshot 2025-08-16 092309" src="https://github.com/user-attachments/assets/5e53aea5-5e70-4eae-8d24-1ee073b21ce9" />
<img width="1252" height="249" alt="Screenshot 2025-08-16 092326" src="https://github.com/user-attachments/assets/c5646d6a-6dfa-4d91-980b-9a3247d36200" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
