# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy package.
2. import scipy package and use linalg function from lu.
3. Using three(P,L,U) variables store lu(arr). 
4. print L and U.
5. End the program.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Sanjay G 
RegisterNumber: 212222230131
*/
import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
P,L,U=lu(arr)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix
Developed by: 
RegisterNumber: 
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![lu decomposition]()
## 1
![image](https://github.com/Sanjay-sg/LU-Decomposition/assets/119559022/9cfc81c9-8cd8-4c67-8abd-a3891b390f11)
## 2
![image](https://github.com/Sanjay-sg/LU-Decomposition/assets/119559022/1bf0b57f-df36-4398-a911-6732335fad84)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

