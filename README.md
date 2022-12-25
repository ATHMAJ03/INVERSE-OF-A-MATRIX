# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import numpy as np
### Step 2: 
We have created a matrix using array and we will find inverse of this.
### Step 3: 
We can find the inverse of the martix by using np.linalg.inv and passing the matrix.
### Step 4: 
Finally, print the value of the inverse of the matrix.

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: ATHMAJ VENUGOPAL
#RegisterNumber:22007603
import numpy as np
A=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
r=np.linalg.inv(A)
print(r)
```
## Output:
![Output](/Screenshot%20from%202022-12-25%2022-16-17.png)
## Result:
Thus the inverse of given matrix is successfully solved using python program

