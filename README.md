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
# Register No: 212224230206
# Developed By: Praveen S
# 1-Norm of a Matrix
import numpy as np
matrix = eval(input())
arr = np.array(matrix)
norm = np.linalg.norm(arr,1)
print("{:.2f}".format(norm))



# 2-Norm of a Matrix
import numpy as np

# Type your code here

matrix = eval(input())
arr = np.array(matrix)
norm = np.linalg.norm(arr,2)
print("{:.2f}".format(norm))



# Infinity Norm of a Matrix

import numpy as np
matrix = eval(input())
arr = np.array(matrix)
norm = np.linalg.norm(arr,np.inf)
print(norm)



```
## Output:
### 1-Norm of a Matrix
<img width="1272" height="841" alt="image" src="https://github.com/user-attachments/assets/e7811a30-bee9-4506-b23a-186f1593f3e9" />


### 2-Norm of a Matrix
<img width="1284" height="924" alt="image" src="https://github.com/user-attachments/assets/d7d8f452-3668-436c-a7ec-a437b0931dc3" />


### Infinity Norm of a Matrix
<img width="1269" height="811" alt="image" src="https://github.com/user-attachments/assets/88d4a016-9d15-4e00-95cd-e7f233332251" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
