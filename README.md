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
# Register No: 22001737
# Developed By: Nandhakumar.G.R
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
print("{:.2f}".format(ans))



# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("{:.2f}".format(ans))



# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))

```
## Output:
### 1-Norm of a Matrix
![1:norm](https://user-images.githubusercontent.com/120230694/213381448-2451e689-79f5-4ecb-a08f-7b2251f7193c.png)


### 2-Norm of a Matrix
![2:norm](https://user-images.githubusercontent.com/120230694/213381487-699f040b-3b45-4013-a207-2eb0046d4aa3.png)


### Infinity Norm of a Matrix
![infinity norm](https://user-images.githubusercontent.com/120230694/213381536-dfcb1ef8-5915-46f7-8383-efff625d39fc.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
