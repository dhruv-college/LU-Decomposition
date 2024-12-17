# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. find the l and u matirx by using numpy and linalg from scipy
2. print the l matrix and u matirx
3. find the lu decomposition by using numpy and lu_factor and lu_solve
4. print the the following matrix

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:Dhruv.D 
RegisterNumber:24900416 
*/
'''Program to find L and U matrix using LU decomposition.
Developed by:Dhruv.D
RegisterNumber:24900416 
'''
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:Dhruv.D
RegisterNumber:24900416
*/
'''Program to solve a matrix using LU decomposition.
Developed by:Dhruv.D
RegisterNumber:24900416
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:

![alt text](<ex 5(1).png>)

![alt text](<ex 5(2).png>)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

