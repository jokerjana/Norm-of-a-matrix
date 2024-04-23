# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# REGISTER NO :212223100014
# DEVELOPED BY:JANARTHANAN B
# 1-Norm of a Matrix

import numpy as np
matrix=eval(input())
one_form=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_form))


# 2-Norm of a Matrix

import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))


# Infinity Norm of a Matrix

import numpy as np
matrix=eval(input())
inf_form=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(inf_form))



```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/jokerjana/Norm-of-a-matrix/assets/147173630/259d254c-81e5-44ea-80e5-828528a457ed)


### 2-Norm of a Matrix
![image](https://github.com/jokerjana/Norm-of-a-matrix/assets/147173630/aa8e081d-cb5d-4a2f-8fbd-ef3523f94b13)

### Infinity Norm of a Matrix
![image](https://github.com/jokerjana/Norm-of-a-matrix/assets/147173630/29072ef9-8d2e-4f83-92f8-6b38f1a34036)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
