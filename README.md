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
![m1](https://user-images.githubusercontent.com/120230694/213381713-8dcd3093-7f85-47c7-ad25-7b2d6bed4e12.png)



### 2-Norm of a Matrix
![m2](https://user-images.githubusercontent.com/120230694/213381746-93d0757b-a1d0-4a35-96a0-c14bbce60476.png)


### Infinity Norm of a Matrix
![m3](https://user-images.githubusercontent.com/120230694/213381776-225103cd-f096-416b-89ee-7ad79b4c13fb.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
