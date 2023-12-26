# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import the numpy module
2. imorting ly from scipy.linalg
3. getting input
4. eval and print the output

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
![lu output 1](https://github.com/Narendran-sec/LU-Decomposition/assets/147473131/7338e6a3-f4c3-4c1a-8302-eb865d661805)
![lu output 2](https://github.com/Narendran-sec/LU-Decomposition/assets/147473131/1a86044b-6b24-418d-8bfb-7dcfe7b8ee40)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

