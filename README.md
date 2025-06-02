# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
```
# 1-Norm
Step 1:Start the program and import the required library (NumPy) to perform matrix operations.
Step 2:Input the matrix from the user in the form of a list of lists (e.g., [[2, -8], [3, 1]]) and convert it into a NumPy array.
Step 3:Use the NumPy function np.linalg.norm(matrix, 1) to calculate the 1-Norm, which is the maximum absolute column sum of the matrix.
Step 4:Store the result in a variable and display it.
Step 5:End the program.

# 2-Norm
Step 1:Start the program and import the NumPy module for numerical operations.
Step 2:Input the matrix from the user as a list of lists and convert it into a NumPy array using np.array().
Step 3:Use the function np.linalg.norm(matrix, 2) to compute the 2-Norm (which is the largest singular value of the matrix).
Step 4:Format and display the result to two decimal places using "{:.2f}".format(result).
Step 5:End the program.

```
## Program:
```
# Register No: 212224230208
# Developed By: PRIYA.B


# 1-Norm of a Matrix

import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,1)
print(result)

# 2-Norm of a Matrix

import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,2)
print("{:.2f}".format(result))

# Infinity Norm of a Matrix

import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(result))

```
## Output:
### 1-Norm of a Matrix

![alt text](<1 norm.png>)

### 2-Norm of a Matrix

![alt text](<2 norm.png>)

### Infinity Norm of a Matrix

![alt text](<i norm.png>)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
