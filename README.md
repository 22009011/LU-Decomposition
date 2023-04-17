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
![Screenshot 2023-04-17 at 23-26-34 Ex05-CR- LU Decomposition Attempt review](https://user-images.githubusercontent.com/118343461/232570684-0f9c294a-bcf2-423b-8e3a-55339408782b.png)
![Screenshot 2023-04-17 at 23-26-53 Ex05-CR- LU Decomposition Attempt review](https://user-images.githubusercontent.com/118343461/232570781-44985177-ebd0-4e58-8f97-85be22d4cbec.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

