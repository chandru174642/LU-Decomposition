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
![Screenshot 2023-12-26 132713](https://github.com/chandru174642/LU-Decomposition/assets/139841798/edd4ac96-3fe2-4c34-97fe-15150648b41b)

![Screenshot 2023-12-26 132733](https://github.com/chandru174642/LU-Decomposition/assets/139841798/5b20faf9-01bc-4a0c-90c6-4f604741f8d3)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

