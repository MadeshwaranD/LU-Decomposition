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
(i) To find the L and U matrix
```
Program to solve a matrix using LU decomposition.
Developed by: Madeshwaran D
RegisterNumber: 212225040212
'''

# Define the matrix A and the vector B from the example
A = np.array([[3, 2, 7], [2, 3, 1], [3, 4, 1]])
B = np.array([4, 5, 7])

# Perform LU decomposition and solve
# lu_factor returns the pivot indices and the LU matrix in a single structure
lu, piv = lu_factor(A)
x = lu_solve((lu, piv), B)

# Print the result
print(x)
```
(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu

'''
Program to find L and U matrix using LU decomposition.
Developed by: madeshwaran D
RegisterNumber: 212225040212
'''

# Define the input matrix A
a = np.array([[3, 2, 7], [2, 3, 1], [3, 4, 1]])

# Perform LU decomposition
# P is the permutation matrix, L is lower triangular, U is upper triangular
p, l, u = lu(a)

# Print the results
print(l)
print(u)
```

## Output:
<img width="1546" height="548" alt="Screenshot 2026-03-27 192942" src="https://github.com/user-attachments/assets/db0537aa-1b4a-4689-a1aa-527ce83b7100" />
<img width="1553" height="636" alt="Screenshot 2026-03-27 193147" src="https://github.com/user-attachments/assets/1f7e3e1c-f306-4aba-8199-d87ae1bab7af" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

