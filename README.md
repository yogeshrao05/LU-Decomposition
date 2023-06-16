# LU Decomposition without zero on the diagonal
5A

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.import numpy library using import statement
2.from scipy package lu() 
3.get input from user and pass it as an array
4. get p,l,u matrix using lu()
5. print L and u matrix

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: yogesh rao S D
RegisterNumber:212222110055 
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)
```


## Output:
![lu decomposition]()


![image](https://github.com/yogeshrao05/LU-Decomposition/assets/122008288/97668b52-7e3a-46d2-b532-560e9f08666d)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

5B

AIM:
To wirte a program to find the lu decomposition of a matrix

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy library using statement.
2. from scipy package import lu_factor() and lu_solve().
3. get two inpute from user and pass it as matrix array. 
4. find lu and pivot value of first matrix using lu_factor().
5. print the solution.

Program:
```
'''Program to solve a matrix using LU decomposition.
Developed by: yogesh rao
RegisterNumber: 212222110055
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=eval(input())
B=eval(input())
lu, piv = lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```
Output:

![image](https://github.com/yogeshrao05/LU-Decomposition/assets/122008288/83f7ab46-bde6-4246-a493-468da8989dc5)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.
