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
# Register No:212222230035
# Developed By:DIVYA K
#RegisterNumber: 212222230035
# 1-Norm of a Matrix
```import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,1)
print("{:.2f}".format(soln))
```



# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: DIVYA K
RegisterNumber: 212222230035
'''
import numpy as np
array=np.array(eval(input()))
n=np.linalg.norm(array,2)
print("{:.2f}".format(n))
```

# Infinity Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: DIVYA K
RegisterNumber: 212222230035
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/divyakumars/Norm-of-a-matrix/assets/119393621/8020d8d4-3e02-4d58-a99e-640922d30ec5)


### 2-Norm of a Matrix
![image](https://github.com/divyakumars/Norm-of-a-matrix/assets/119393621/67bcca90-2707-47fb-9023-32d5d85e6508)


### Infinity Norm of a Matrix
![image](https://github.com/divyakumars/Norm-of-a-matrix/assets/119393621/2c0eba8f-56d8-4d5a-aa16-7fcc68e928a2)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
