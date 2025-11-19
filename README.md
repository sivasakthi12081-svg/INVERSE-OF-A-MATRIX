# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Write the augmented matrix [A | I].
### Step 2: 
Use row operations to convert A into I.
### Step 3: 
Apply the same row operations on I to get A⁻¹.
### Step 4: 
Read the inverse from the right side of the final matrix.

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: Sivasakthi S
#RegisterNumber:25017123
import numpy as np
A=np.array([[2,1,1],[1,1,1],[1,-1,2]])
inverse=np.linalg.inv(A)
print(inverse)
```
## Output:
<img width="1920" height="1200" alt="Exp-3" src="https://github.com/user-attachments/assets/ae67406f-c84b-417f-97db-651d7e728ad1" />
<img width="1920" height="1200" alt="Exp3" src="https://github.com/user-attachments/assets/c8663f9d-536e-46f7-a68d-f38527fe067a" />


## Result:
Thus the inverse of given matrix is successfully solved using python program

