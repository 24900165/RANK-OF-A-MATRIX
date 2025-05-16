# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
 Import the NumPy module to use its built-in functions for matrix and linear algebra operations.
### Step 2: 
Prepare the list of coefficients from the linear equations and store them in a 2D NumPy array.
### Step 3: 
Prepare the list of constants (right-hand side values of the equations) and store them in a 1D NumPy array.

### Step 4:
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 5:
 Display the result (values of the variables).
 ### Step 6:
 End the program.
## Program:
```
import numpy as np
A=np.array( [[3,2,5],[1,1,2],[3,3,6]])
result=np.linalg.matrix_rank(A)
print(result)
```
## Output:
![alt text](<Screenshot 2025-05-16 180910.png>)
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

