# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
# Algorithm: 
## Step 1 : Input the matrix ( A ).
## Step 2 : Convert ( A ) to row echelon form.
## Step 3 : Count the number of rows with non-zero element.
## Step 4 : The rank is equal to the count of non-zero rows.

## Program:
```
#Program to find the rank of a matrix.
#Developed by: Tharun.V
#RegisterNumber:212224230290
import numpy as np
a=np.array([[3,2,5],[1,1,2],[3,3,6]])
sum=np.linalg.matrix_rank(a)
print(sum)
```
## Output:
![Screenshot 2025-04-22 231043](https://github.com/user-attachments/assets/54779970-7bb6-4856-88a1-97a7da7357bc)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

