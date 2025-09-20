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
Developed by: KISHORE J
RegisterNumber: 25000178 
*/
import numpy as np 
from scipy.linalg import lu
a = np.array(eval(input()))
_,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: KISHORE J
RegisterNumber: 25000178
*/
import numpy as np
from scipy.linalg import lu_factor ,lu_solve
a = np.array([[3, 2, 7], [2, 3, 1], [3, 4, 1]])
b = np.array([4,5,7])
lp = lu_factor(a)
x = lu_solve(lp ,b)
print(x)
```

## Output:
(i)
<img width="1155" height="426" alt="Screenshot 2025-09-20 084039" src="https://github.com/user-attachments/assets/f4e2bd40-8e96-4861-834b-9c2ea08ddc40" />

(ii)
<img width="845" height="161" alt="Screenshot 2025-09-20 084104" src="https://github.com/user-attachments/assets/d4d9e21f-dbf1-4476-a0ae-101d1bb7c0bd" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.# LU-Decomposition
