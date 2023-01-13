# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy,scipy.linalg python library as n,lu
2. Get input from user as x
3. convert x into array 
4. lu() returns three values assign it as p,l,u 
5. Then print l matrix and u matrix

## Program:
```py
'''Program to find L and U matrix using LU decomposition.
Developed by: SHALINI V
RegisterNumber: 22009257
'''
import numpy as n
from scipy.linalg import lu
x=eval(input())
a=n.array(x)
p,l,u=lu(a)
print(l)
print(u)
```
```py
'''Program to solve a matrix using LU decomposition.
Developed by: SHALINI V
RegisterNumber: 22009257
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=eval(input())
res=lu_factor(a)
sol=lu_solve(res,b)
print(sol)
```

## Output:
![lu decomposition](/LU.jpg)
![lu](/lu2.jpg)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

