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
# 1-Norm of a Matrix

'''
Program to find the 1-Norm of a matrix.
Developed by : yuva krishna k
Register number:212222110056

'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
print("{:.2f}".format(ans))

# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: yuva krishna k
RegisterNumber: 212222110056
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("{:.2f}".format(ans))

# Infinity Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: yuva krishna k
RegisterNumber: 212222110056
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))

```
## Output:
### 1-Norm of a Matrix
![Screenshot (60)](https://github.com/Yuvakrishna0/Norm-of-a-matrix/assets/117915037/cb060f73-441e-4f27-8ddd-5557ee962900)


<br>

### 2-Norm of a Matrix
![Screenshot (61)](https://github.com/Yuvakrishna0/Norm-of-a-matrix/assets/117915037/b702bea3-cde4-4958-aa7c-dd7478563dbe)

<br>

### Infinity Norm of a Matrix
![Screenshot (62)](https://github.com/Yuvakrishna0/Norm-of-a-matrix/assets/117915037/6d08991a-d38b-459c-bb84-4989e414ac31)

<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
