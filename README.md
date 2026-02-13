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
# Register No:212224230082
# Developed By:Harini P
# 1-Norm of a Matrix

import numpy as np
A=np.array(eval(input()))
norm_1=np.linalg.norm(A,1)
print("{:.2f}".format(norm_1))

# 2-Norm of a Matrix

import numpy as np
A=np.array(eval(input()))
norm_l2=np.linalg.norm(A,2)
print("{:.2f}".format(norm_l2))


# Infinity Norm of a Matrix

import numpy as np
A=np.array(eval(input()))
norm_inf=np.linalg.norm(A,np.inf)
print("{:.2f}".format(norm_inf))



```
## Output:
### 1-Norm of a Matrix
<img width="955" height="286" alt="image" src="https://github.com/user-attachments/assets/980cdb7f-0a65-4d40-ab7f-9849c72b8b02" />


### 2-Norm of a Matrix
<img width="646" height="326" alt="image" src="https://github.com/user-attachments/assets/4e19ce98-67ae-4cae-9641-3cc5764e4dd2" />


### Infinity Norm of a Matrix
<img width="668" height="293" alt="image" src="https://github.com/user-attachments/assets/5dbe4a58-dc63-4635-aa80-3e9d603e0d2e" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
