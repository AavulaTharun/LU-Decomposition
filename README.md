# LU Decomposition without zero on the diagonal

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. start the program
2. Enter the values 
3. Display the progarm 
4. End the program

## Program:
```python
'''Program to find L and U matrix using LU decomposition.
Developed by:A.Tharun
RegisterNumber:21003406 
'''

# To print L and U matrix
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
## output:
![output](https://github.com/AavulaTharun/LU-Decomposition/blob/main/tt.JPG?raw=true)

## progtam:
```python
'''Program to solve a matrix using LU decomposition.
Developed by:A.Tharun 
RegisterNumber:21003406 
'''

# To print X matrix (solution to the equations)
import numpy as np
import scipy
from scipy.linalg import lu_factor,lu_solve
A=([[3, 2, 7], [2, 3, 1], [3, 4, 1]])
B=([4, 5, 7])
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```

## Output:
![output](https://github.com/AavulaTharun/LU-Decomposition/blob/main/t2.JPG?raw=true)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

