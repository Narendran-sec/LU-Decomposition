# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: NARENDRAN . K
RegisterNumber: 23013500
*/

import numpy as np
from scipy.linalg import lu
a=eval(input())
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: NARENDRAN . K
RegisterNumber: 23013500
*/
import numpy as np
from scipy.linalg import lu,solve
a=eval(input())
b=eval(input())
p,l,u=lu(a)
x=solve(a,b)
print(x)
```

## Output:
![Alt text](<lu output 1.png>)
![Alt text](<lu output 2.png>)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

