# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Set the first column of L as the first column of the matrix.
2. Use Gaussian elimination to update matrix A to U and compute L.
3. Separate L and U matrices from the modified matrix A. 
4.  Output the decomposed L and U matrices as the result.

## Program:
(i) To find the L and U matrix
```PYTHON
'''Program to find L and U matrix using LU decomposition.
Developed by: M B ANU VARSHINI
RegisterNumber: 23008712
'''
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```PYTHON
'''Program to solve a matrix using LU decomposition.
Developed by: M B ANU VARSHINI
RegisterNumber: 23008712
'''
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
a=np.array(arr)
b=np.array(constant)
result=lu_factor(a)
solution=lu_solve(result,b)
print(solution)
```

## Output:
![lu](https://github.com/anu-varshini11/LU-Decomposition/assets/138969827/54ca120e-99ca-40c5-a83b-1a55ad068d95)
![lu1](https://github.com/anu-varshini11/LU-Decomposition/assets/138969827/1a46c124-9d10-4adb-9231-7d1c105b7fdf)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

