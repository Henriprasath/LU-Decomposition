# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .  
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X'

## Program:
(i)Program to find L and U matrix using LU decomposition.
```
Program to find L and U matrix using LU decomposition.
Developed by: HENRIPRASATH.S    
RegisterNumber: 23003595

from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) Program to solve a matrix using LU decomposition.
```
Program to solve a matrix using LU decomposition.
Developed by: HENRIPRASATH.S
RegisterNumber: 23003595

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
+![Screenshot 2023-12-27 225402](https://github.com/Henriprasath/LU-Decomposition/assets/144979077/8582c8c0-3e3d-4043-9cb9-3ac94f6acda3)

![Screenshot 2023-12-27 225422](https://github.com/Henriprasath/LU-Decomposition/assets/144979077/fcc4cd09-965a-482c-b635-a6f0ffcea0a6)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

