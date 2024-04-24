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
```
#Python
# Register No: 212223230025
# Developed By: ASHWINA K N

# 1-Norm of a Matrix
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(two_matrix))



# 2-Norm of a Matrix

import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))




# Infinity Norm of a Matrix

import numpy as np
matrix=np.array(eval(input()))
ans =np.linalg.norm(matrix,np.inf)
norm_of_matrix = '{:.2f}'.format(ans)
print(norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix:

![EX-7 1](https://github.com/Ashwinakn/Norm-of-a-matrix/assets/152128332/06f9c99d-2cb8-42c3-8d37-b345b82bbdd2)


### 2-Norm of a Matrix

![EX-7 2](https://github.com/Ashwinakn/Norm-of-a-matrix/assets/152128332/2f2dfe7a-34b0-4fbd-95d3-65af7b94f350)


### Infinity Norm of a Matrix

![EX-7 3](https://github.com/Ashwinakn/Norm-of-a-matrix/assets/152128332/628f4a0d-9c37-4a3c-acbe-01b629262671)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
