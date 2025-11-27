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
#Program to find 1-norm of a matrix.
#Developed by: MUTHUAKASH M
#RegisterNumber: 25016467
import numpy as np
a=eval(input())
b=np.linalg.norm(a,1)
print(b)



# 2-Norm of a Matrix

#Program to find 2-norm of a matrix.
#Developed by: MUTHUAKASH M
#RegisterNumber: 25016467
import numpy as np
a=eval(input())
b=np.linalg.norm(a,2)
print(f"{b:.2f}")


# Infinity Norm of a Matrix

#Program to find Infinity-norm of a matrix.
#Developed by: MUTHUAKASH M
#RegisterNumber: 25016467
import numpy as np
a=eval(input())
b=np.linalg.norm(a,np.inf)
print(b)



```
## Output:
### 1-Norm of a Matrix
<img width="1220" height="740" alt="image" src="https://github.com/user-attachments/assets/60aef2a5-65ce-4a08-a5e0-74a2a1cd1da9" />

### 2-Norm of a Matrix
<img width="1207" height="780" alt="image" src="https://github.com/user-attachments/assets/b75de437-ae45-4f97-93f6-0515cbacf93d" />

### Infinity Norm of a Matrix
<img width="1212" height="737" alt="image" src="https://github.com/user-attachments/assets/3d21fdec-1297-4ae1-875d-66a4fa8ce024" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
