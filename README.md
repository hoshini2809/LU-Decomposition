# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable.
4.Print the variable 'X'.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Hoshini S
RegisterNumber:2305003006

import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Hoshini S
RegisterNumber:2305003006

import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
*/
```

## Output:

![Screenshot 2024-05-23 092610](https://github.com/hoshini2809/LU-Decomposition/assets/170595101/476b72c9-2edf-4778-8790-53ac6e0cb705)


![Screenshot 2024-05-23 092859](https://github.com/hoshini2809/LU-Decomposition/assets/170595101/3896c0da-9f07-4755-8e61-a14e1d0ea55f)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

