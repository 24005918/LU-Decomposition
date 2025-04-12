# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2.Get input from user and print L and U matrix by 'print' .
3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable
4.print the variable 'X'

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
RegisterNumber: 212224230252
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
![lu decomposition]()
![{45C3637C-0E9D-48F1-8A2F-BD5DDF842A79}](https://github.com/user-attachments/assets/957fcaae-f274-4cc5-bd7b-d930f90313f5)
![{3AD32640-6A73-45B4-990D-497C54F3703E}](https://github.com/user-attachments/assets/d518e87e-6699-4f46-a7ba-0a601c34f7f6)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

