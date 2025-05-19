# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module and scipy.linalg module to use the built-in functions for calculation.
2. Prepare the lists from each linear equations and assign in np.array().
3. Perform scipy.linalg.lu to find the pivot table, lower triangle and upper triangle matrix.
4. End the Program.

Program: 
 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: SANTHOSH V
RegisterNumber: 212224230252
*/
```
from scipy.linalg import lu

a=eval(input())

p,l,u=lu(a)

print(l)

print(u)

(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: SANTHOSH V
RegisterNumber:  212224230252
*/
```
import numpy as np

from scipy.linalg import lu_factor, lu_solve

a=eval(input())

b=eval(input())

lu,plv=lu_factor(a)

x=lu_factor(a)

x=lu_solve((lu,plv),b)

print(x)


## Output:
![{A59AB312-7637-458F-AE09-FD20B2B02817}](https://github.com/user-attachments/assets/e3002cd7-a2c5-4e77-b602-6663972b891f)
![{F27580E0-0124-4133-9437-06B229B9AF39}](https://github.com/user-attachments/assets/3f61e79b-d4b4-44e4-94c2-4a5df94194e0)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

