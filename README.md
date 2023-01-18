# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Read the elements of augmented matrix into arrays a and b.
2. Calculate elements of L and U.
3. Print elements of L and U .
4. Find V by solving LV = B by forward substitution.
5. Find X by solving LX = V by backward substitution.
6. Print Array X as the solution.

## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by: LOKESH RAHUL V V
RegisterNumber: 22004702

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: LOKESH RAHUL V V 
RegisterNumber:22004702

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)

```

## Output:
(i)
![image](https://user-images.githubusercontent.com/118423842/213168881-837900d0-fb31-4e12-bd46-c4e9cf74f9fb.png)

(ii)
![image](https://user-images.githubusercontent.com/118423842/213169075-4f785b33-15ca-4cb7-8968-dd0575e7601f.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

