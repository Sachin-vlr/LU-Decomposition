# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.  import numpy library using import statement.
2.  From scipy package import lu().
3.  Get input from user and pass it as an array.
4.  Get P, L U martix using lu()
5.  print L and U matrix

## Program:
(i) To find the L and U matrix
```python
#Program to find the L and U matrix.
#Developed by: SACHIN.C
#RegisterNumber: 22001187
import numpy as np
from scipy.linalg import lu
A=eval(input())
P,L,U=lu(A)
print(L)
print(U)
```

(ii) To find the LU Decomposition of a matrix
```python
#Program to find the LU Decomposition of a matrix.
#Developed by: SACHIN.C
#RegisterNumber: 22001187
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![output](/lu1.png)
![output](/lu2.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

