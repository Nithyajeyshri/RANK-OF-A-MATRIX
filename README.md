# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step1: Import NumPy library for matrix operations.
### Step2: Define the matrix using np.array().
### step3: Use np.linalg.matrix_rank() to compute the rank of the matrix.
### Step4:Print the result to display the rank.
 
## Program:
```
#Program to find the rank of a matrix.
#Developed by: NITHYA JEY SHRI S S
#RegisterNumber: 212225040288

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrixA=np.array([[1,2,3],[3,6,9]])
rank=np.linalg.matrix_rank(matrixA)
print(rank)
```
## Output:
<img width="1482" height="701" alt="Screenshot 2026-05-01 131520" src="https://github.com/user-attachments/assets/18a8c445-5266-4709-9798-5deedc27ed2a" />
<img width="1475" height="305" alt="Screenshot 2026-05-01 131532" src="https://github.com/user-attachments/assets/d453e948-6737-4797-baac-eb5105aea8e3" />
## Result:

Thus the rank for the given matrix is successfully solved by  using a python program.

