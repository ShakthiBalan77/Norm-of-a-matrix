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
# Register No:25016098
# Developed By: SHAKTHI BALAN V
```

```
# 1-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,1)
print(b)
```

```
# 2-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,2)
print(round(b,2))
```

```
# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,np.inf)
print(b)

```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>

### 2-Norm of a Matrix
<br>
<br>
<br>

### Infinity Norm of a Matrix
<br>
<img width="952" height="854" alt="Screenshot 2025-12-19 174029" src="https://github.com/user-attachments/assets/4c8fe2ac-9af5-4233-ba0c-3a66d55cd1a2" />
<br>
<img width="974" height="815" alt="Screenshot 2025-12-19 174220" src="https://github.com/user-attachments/assets/4434a3f9-5e25-44c6-b0cf-cb7a172a8c03" />
<br>
<img width="995" height="691" alt="Screenshot 2025-12-19 174259" src="https://github.com/user-attachments/assets/bf7d8c99-74e4-49a2-bd64-0faca8e7d8cd" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
