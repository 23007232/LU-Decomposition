# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import libraries
2. get the matrix from the user
3. find the l and u
4. print the solution

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: pavithra p
RegisterNumber: 23007232
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: pavithra p
RegisterNumber: 23007232
'''
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
sol=lu_solve(result,B)
print(sol)


```

## Output:
![image](https://github.com/23007232/LU-Decomposition/assets/139115574/14704c2c-8b61-4e0f-858d-099abda87e4b)
![image](https://github.com/23007232/LU-Decomposition/assets/139115574/55a363e9-2e3f-4cdd-a03e-408aa071778b)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

