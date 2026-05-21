# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program
2. Import the necessary libraries(numpy,scipy.linalg)
3. Define the matrix using numpy
4. Use lu(),lu_solve(),lu_factor() to get the solutions
5. End the program
   
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: FARHAAN THAYYIB L 
RegisterNumber: 212225230069
*/
```
```

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np
from scipy.linalg import lu

a = np.array(eval(input()))

p, l, u = lu(a)

print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: FARHAAN THAYYIB L
RegisterNumber: 212225230069
*/
```
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

a = np.array(eval(input()), dtype=float)
b = np.array(eval(input()), dtype=float)

x = np.linalg.solve(a, b)

print(x)
```

## Output:
![lu decomposition]()
<img width="624" height="712" alt="image" src="https://github.com/user-attachments/assets/a755f149-f8ba-4156-bfda-81f3099b2cf1" />
<img width="664" height="550" alt="image" src="https://github.com/user-attachments/assets/1029f069-9a24-4733-973b-6b0d7d81ef8c" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

