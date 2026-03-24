<img width="1282" height="368" alt="image" src="https://github.com/user-attachments/assets/fec7deaf-7fa7-460a-8d56-589bae5c46d7" /># Norm of a matrix
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
# Register No:25017572
# Developed By:KISHOOR I
# 1-Norm of a Matrix
# Register No:25003270
# Developed By:ASHFAK N

# 1-Norm of a Matrix
```
import numpy as np

i=np.array(eval(input()))

o=np.linalg.norm(i,1)

print(o)

# 2-Norm of a Matrix

import numpy as np

i=np.array(eval(input()))

o=np.linalg.norm(i,2)

print(f"{o:.2f}")


# Infinity Norm of a Matrix

import numpy as np

i=np.array(eval(input()))

o=np.linalg.norm(i,np.inf)

print(o)

```
## Output:
### 1-Norm of a Matrix

<img width="1282" height="368" alt="image" src="https://github.com/user-attachments/assets/b7b709e5-86d5-411b-8948-eeebd1e8d309" />


### 2-Norm of a Matrix

<img width="1282" height="368" alt="image" src="https://github.com/user-attachments/assets/b0a8e171-1292-41e7-8b26-25005be83070" />


### Infinity Norm of a Matrix

<img width="1282" height="368" alt="image" src="https://github.com/user-attachments/assets/1f0080d8-152a-431a-8db0-77c97adbc325" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
