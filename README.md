# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step 1:
Get the input matrix using np.array()   
## Step 2:
Find the 2-norm of the matrix using np.linalg.norm()
## Step 3:
Print the norm of the matrix in two decimal places.
## Program:
```
'''
Program to find 1-norm of a matrix.
Developed by: Priyadharshini.P
Register Number: 23013604
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix= "{:.2f}".format(ans)
print(Norm_of_matrix)
```

# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: Priyadharshini.P
RegisterNumber: 23013604
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
# Infinity Norm of a Matrix
```
'''
Program to find infinity Norm of a matrix.
Developed by: Priyadharshini.P
RegisterNumber: 23013604
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-30 183057](https://github.com/priyadharshini210/Norm-of-a-matrix/assets/148514638/4e64fb43-a71a-430c-8ed9-f74e36dae2eb)
<br>
<br>
<br>

### 2-Norm of a Matrix
![Screenshot 2023-12-30 183239](https://github.com/priyadharshini210/Norm-of-a-matrix/assets/148514638/ce2174f2-70d4-4c0c-94c0-6fc93f182058)
<br>
<br>
<br>

### Infinity Norm of a Matrix
![Screenshot 2023-12-30 183507](https://github.com/priyadharshini210/Norm-of-a-matrix/assets/148514638/a532e017-055c-4da7-a056-4933912a771f)
<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
