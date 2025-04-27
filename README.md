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
# Register No:24000724
# Developed By:Deepika.V
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat, 1)
NORM = "{:.2f}".format(ans)
print(NORM)



# 2-Norm of a Matrix
import numpy as np
# Type your code here
mat = np.array(eval(input()))
ans = np.linalg.norm(mat, 2)
NORM = "{:.2f}".format(ans)
print(NORM)



# Infinity Norm of a Matrix
import numpy as np
matrix = np.array(eval(input()))
red = np.max(np.sum(np.abs(matrix), axis=1))
print(f"{red:.2f}")



```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/e4d47296-8233-4394-aa06-3119c462bb4a)


### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/c344d30a-3986-4001-8003-548578a23ab5)


### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/a077476a-f022-431e-b9ee-f469752fbcbe)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
