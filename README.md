# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Here are **5 clear algorithm steps** for your LU Decomposition experiment:

## Algorithm

1. **Start the program** and import required libraries like NumPy and SciPy.
2. **Define the input matrix** ( A ) and (if needed) vector ( B ).
3. **Apply LU Decomposition** using a suitable function to decompose matrix ( A ) into Lower triangular matrix ( L ) and Upper triangular matrix ( U ).
4. **Solve the system (optional)** using the decomposed matrices to find the solution vector ( X ).
5. **Display the results** (matrices ( L ), ( U ), and solution ( X )) and stop the program.

## Program:
```
Program to solve a matrix using LU decomposition.
Developed by: Madeshwaran D
RegisterNumber: 212225040212
'''

(i) To find the L and U matrix

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)


(ii) To find the LU Decomposition of a matrix
/*
Program to find the LU Decomposition of a matrix.
Developed by: Madeshwaran D
RegisterNumber: 212225040212
*/
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
<img width="1207" height="778" alt="image" src="https://github.com/user-attachments/assets/8352557d-e9da-4ee7-a5f0-6850044d2b46" />

## Output:
<img width="1211" height="508" alt="image" src="https://github.com/user-attachments/assets/3e94e6fb-6c1f-42ac-b512-aa423d2d23ef" />
<img width="1211" height="271" alt="image" src="https://github.com/user-attachments/assets/a1e7e892-a252-48e4-b988-5ce40f790e3b" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

