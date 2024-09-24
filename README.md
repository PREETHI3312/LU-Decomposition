# DATE:
# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

  1. Import numpy extension and scipy.linalg extension
  2.Initialize the matix values
  3. Use lu functions from imported extensions
  4. Print the output

## Program:
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
/*
Program to find the L and U matrix.
Developed by: A K PREETHI
RegisterNumber: 212223230156
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: PREETHI A K
RegisterNumber: 212223230156
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)
```

## Output:
![lu decomposition]()
![image](https://github.com/user-attachments/assets/4642a31c-f272-484a-a4aa-d2c5706d2224)
![image](https://github.com/user-attachments/assets/8c313324-6070-414e-9988-f7adaf77efaf)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

