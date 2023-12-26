# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
```
1.STEP:
Import numpy module to use the bulit-in functions for calcukation
2. STEP:
From scipy.linalg module import lu to find the L and U matrix
3.STEP:
Get a input from the user and apply lu function.
4.STEP:
Print L for L matrix and print U for U matrix
5.STEP:
End of program.
## Program:
(i) To find the L and U matrix
```
```
'''Program to find L and U matrix using LU decomposition.
Developed by: CHANDRU.P
RegisterNumber: 23007250
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
Developed by: CHANDRU.P
RegisterNumber: 23007250
'''
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)


```

## Output:
![Screenshot 2023-12-26 132713](https://github.com/AkilaMohan/LU-Decomposition/assets/139841798/bd902316-8831-45ed-9796-bfc38b8bd532)

![Screenshot 2023-12-26 132733](https://github.com/AkilaMohan/LU-Decomposition/assets/139841798/50582602-6db2-491f-b6b3-81a4c3acfe6a)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

