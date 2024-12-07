# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: 
RegisterNumber: 
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: nithishkumar s
RegisterNumber:24900655
import numpy as np
from scipy.linalg import lu_factor,lu_solve

AMatrix=np.array(eval(input()),dtype='i')
BMatrix=np.array(eval(input()),dtype='i')
XMatrix=lu_factor(AMatrix)
solution=lu_solve(XMatrix,BMatrix)
print(solution)


*/
```

##![alt text](<Screenshot 2024-12-07 194235.png>) Output:

![alt text](<Screenshot 2024-12-07 194246.png>)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

