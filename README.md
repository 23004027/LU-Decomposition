# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

### Algorithm
1. Import the numpy module and scipy.linalg module to use the built-in functions for calculation.
2. Prepare the lists from each linear equations and assign in np.array()
3. Perform scipy.linalg.lu() to find the pivot table, lower traingle and upper triangle matrix.
4. End the Program
## Program:
(i) To find the L and U matrix
```python
Program to find the LU Decomposition of a matrix.
Developed by:vignesh.v
RegisterNumber:23004027 
import numpy as np
a=eval(input())
from scipy.linalg import lu
b=np.array(a)
p,l,u=lu(b)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```python
Program to find the LU Decomposition of a matrix.
Developed by:vignesh.v
RegisterNumber:23004027
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
c=eval(input())
b=np.array(a)
d=np.array(c)
l,p=lu_factor(b)
x=lu_solve((l,p),d)
print(x) 
```

## Output:
![Screenshot 2023-12-28 214049](https://github.com/23004027/LU-Decomposition/assets/138956447/241b7ea0-ad11-4a22-ba5b-cdcbf1e2c8e7)

![Screenshot 2023-12-28 214241](https://github.com/23004027/LU-Decomposition/assets/138956447/186c4651-2b69-49f3-bfd2-5dc000785338)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

