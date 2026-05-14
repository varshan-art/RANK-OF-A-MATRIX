# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step 1: Import the numpy module to use the built-in functions for calculation
Step 2: Prepare the lists from each linear equations and assign in np.array()
Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
Step 4: End the program
## Program:
```
#Program to find the rank of a matrix.
#Developed by: SRI VIJAY VARSHAN G
#RegisterNumber: 212225240157

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([[1,2,3], [3,6,9]])
X=np.linalg.matrix_rank(A)
print(X)

```
## Output:
<img width="1271" height="792" alt="image" src="https://github.com/user-attachments/assets/f710aa92-b344-4c40-87fb-bb7046d9c93c" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

