# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation.
### Step 2: Prepare the lists from each equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program
## Program:
```
import numpy as np
A = np.array([ [2, -3, 0], [2, -5, 0], [0,  0, 3]
], dtype=float)
eigen_values, eigen_vectors = np.linalg.eig(A)
print("Eigen values are", eigen_values, "and Eigen Vectors are", eigen_vectors)
```
## Output:
<img width="1304" height="765" alt="image" src="https://github.com/user-attachments/assets/a1799e74-c0c4-4821-b8c8-3fc2eeffb32b" />
<img width="1260" height="823" alt="image" src="https://github.com/user-attachments/assets/f4f0bc38-2ccc-4e84-a44d-c48620c9cbfb" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
