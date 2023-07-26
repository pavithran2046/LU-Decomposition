# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.  Import the numpy module and scipy.linalg module to use the built-in functions for calculation.
2. Prepare the lists from each linear equations and assign in np.array()
3. Perform scipy.linalg.lu() to find the pivot table, lower traingle and upper triangle matrix.
4. end program

## Program:
(i) To find the L and U matrix
```python
'''Program to find L and U matrix using LU decomposition.
Developed by: pavithran S
RegisterNumber: 23001643
'''
import numpy as np
a=eval(input())
from scipy.linalg import lu
b=np.array(a)
p,l,u=lu(b)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
``` python
'''Program to solve a matrix using LU decomposition.
Developed by: pavithran S
RegisterNumber: 23001643
'''
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a= eval(input())
c= eval(input())
b=np.array(a)
d=np.array(c)
l,p=lu_factor(b)
x=lu_solve((l,p),d)
print(x)
```

## Output:
![output](/Screenshot%202023-07-26%20183823.png)
![output](/Screenshot%202023-07-26%20183937....png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

