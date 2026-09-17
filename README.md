# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:Import the NumPy library using import numpy as np.
### Step 2: Define the given matrix using the np.array() function
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: Display the rank of the matrix using the print() function.

## Program:
```
#Program to find the rank of a matrix.
#Developed by: Nather Nabeel S A C
#RegisterNumber:212224100040

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array( [[5,-3,-10],[2,2,-3],[-3,-1,5]])
solution=np.linalg.matrix_rank(a)
print(solution)

```
## Output:


<img width="1447" height="897" alt="image" src="https://github.com/user-attachments/assets/f704cab6-e78c-4d47-975c-96f56c10acd8" />


## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

