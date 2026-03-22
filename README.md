# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

1.Start the program

2.Import the necessary libraries(numpy,scipy.linalg).|

3.Define the matrix using numpy

4.Use lu(),lu_solve(),lu_factor() to get the solutions

5.End the program 

## Program:

(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.

Developed by: RISHI KUMAR E V
RegisterNumber: 212225230227


import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np
from scipy.linalg import lu
matrix = eval(input())
P,L,U = lu(matrix)
print(L)
print(U)

*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.

Developed by: RISHI KUMAR E V
RegisterNumber: 212225230227

import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)

*/
```

## Output:

<img width="1236" height="867" alt="image" src="https://github.com/user-attachments/assets/09e1b666-0174-4fa7-ab20-c9cd5f4d8bc4" />
<img width="1067" height="780" alt="image" src="https://github.com/user-attachments/assets/ae374769-3ccf-485e-bc97-7ee895dea4cd" />


## Result:

Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

