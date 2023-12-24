# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy into the program.
2. Get input from the user.
3. Use array() fuction and lu() function.
4. Print the output.

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: S.Sanjay Balaji
RegisterNumber: 23005804
'''
from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: S.Sanjay Balaji
RegisterNumber: 23005804
'''

# To print X matrix (solution to the equations)
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)
```

## Output:
i)
![image](https://github.com/SanjayBalaji0/LU-Decomposition/assets/145533553/409f8f00-b51a-4b2d-9b3a-a2835b00e9d4)

ii)
![image](https://github.com/SanjayBalaji0/LU-Decomposition/assets/145533553/7d527d3a-0142-4fa0-adf5-be04256846f3)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

