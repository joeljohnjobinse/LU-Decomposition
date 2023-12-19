# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
(i)
1. Import lu from scipy.linalg package
2. Import numpy module
3. Create the matrix
4. Use lu to find the L and U matrix
5. Print the L and U matrix

(ii)
1. Import lu_factor and lu_solve from scipy.linalg package
2. Import numpy module
3. Create the matrix
4. Take a constant as input
5. Use lu_factor to find the factor
6. Use lu_solve to find the solution
7. Print the solution

## Program:
(i) To find the L and U matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: Joel John Jobinse
RegisterNumber: 212223240062
'''
from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to solve a matrix using LU decomposition.
Developed by: Joel John Jobinse
RegisterNumber: 212223240062
'''

from scipy.linalg import lu_factor, lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)
*/
```

## Output:
![maths-exp5](https://github.com/joeljohnjobinse/LU-Decomposition/assets/138955488/34fb915a-8515-4602-87cd-968f7a977ea4)
![maths-exp5-2](https://github.com/joeljohnjobinse/LU-Decomposition/assets/138955488/aa0d5582-8a04-4d67-9a1c-755f522496b6)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

