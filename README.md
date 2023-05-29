# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.   Read the elements of augmented matrix into arrays
2.   Calculate elements of L and U
3.   Print elements of L and U
4.   Find V by solving LV = B by forward substitution 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: S.ROSELIN MARY JOVITA
RegisterNumber: 212222230122
*/
```
```
import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
P,L,U=lu(arr)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: S.ROSELIN MARY JOVITA
RegisterNumber:212222230122 
*/
```
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=eval(input())
B=eval(input())
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```

## Output:


![LU DECOMPOSITION 1](https://github.com/Roselinjovita/LU-Decomposition/assets/119104296/5963859d-2a95-4a71-b60c-93d20116e541)




![LU DECOMPOSITION 2](https://github.com/Roselinjovita/LU-Decomposition/assets/119104296/af541c9c-aae7-4a47-981d-35182fffaaf9)





## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

