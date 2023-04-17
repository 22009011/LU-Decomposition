# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

1.Import numpy package
2.Import lu from scripy.linalg
3.Get the input of the array
4.Print the output.


## Program:
(i) To find the L and U matrix
```

Program to find the L and U matrix.
Developed by: Thanjiyappan.k
RegisterNumber: 212222240108

import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
P,L,U=lu(arr)
print(L)
print(U)


```
(ii) To find the LU Decomposition of a matrix
```

Program to find the LU Decomposition of a matrix.
Developed by: Thanjiyappan.k
RegisterNumber: 212222240108

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x))

```

## Output:
![Screenshot 2023-04-17 at 23-03-52 Ex05-CR- LU Decomposition Attempt review](https://user-images.githubusercontent.com/118343461/232569110-44a1adc5-56b9-4da5-b7b9-5da45b19806c.png)
![Screenshot 2023-04-17 at 23-03-01 Ex05-CR- LU Decomposition Attempt review](https://user-images.githubusercontent.com/118343461/232569157-1eb63d1e-bf29-4c85-9830-7747934f3b3c.png)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

