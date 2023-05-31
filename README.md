# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Import numpy package as np

2.From scipy package import lu

3.Get input from the user

4.Print result

## Program:
(i) To find the L and U matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: M.CHANDRU
RegisterNumber: 212222230026
'''
import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
P,L,U=lu(arr)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to solve a matrix using LU decomposition.
Developed by: M.CHANDRU
RegisterNumber: 212222230026
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=np.array([[3, 2, 7], [2, 3, 1], [3, 4, 1]])
B=np.array([4, 5, 7])
LU,P=lu_factor(arr)
res=lu_solve((LU,P),B)
print(res)
*/
```

## Output:
(i) To find the L and U matrix:
![Screenshot (82)](https://github.com/chandrumathiyazhagan/LU-Decomposition/assets/119393023/366af220-3947-4831-809f-19e328929c42)
(ii) To find the LU Decomposition of a matrix:
![Screenshot (82)](https://github.com/chandrumathiyazhagan/LU-Decomposition/assets/119393023/ea4a4725-2b1d-4d77-94a6-546a71200d4e)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

