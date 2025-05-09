# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step1 : Form Augmented Matrix: Combine matrix A with identity matrix I → [A | I].

### Step 2: Make Pivot = 1: For each row i, divide the row by A[i][i].

### Step 3: Eliminate Other Entries in Column: For every other row j ≠ i, subtract A[j][i] * row_i from row j to make column i zero.

### Step 4: Repeat for All Rows: Continue until the left side of the augmented matrix becomes identity I.

### Step 5: Extract Inverse: The right side of the augmented matrix is the inverse A⁻¹.

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: RAGA SUSANTH
#RegisterNumber: 212224230217
import numpy as np
A=np.array([[6,2,3],[3,1,1],[10,3,4]])
result=np.linalg.inv(A)
print(result)
```
## Output:
![Screenshot 2025-04-17 143429](https://github.com/user-attachments/assets/01a59575-e470-4344-ba9e-997dd291965e)

## Result:
Thus the inverse of given matrix is successfully solved using python program

