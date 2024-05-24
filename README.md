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
# Register No:2305002017
# Developed By: Poovarasu V
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
# 2-Norm of a Matrix
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


```
## Output:
### 1-Norm of a Matrix
![hh](https://github.com/Poovarasu8/Norm-of-a-matrix/assets/155505954/71173776-3653-4edf-bafd-74347dadfc0c)

### 2-Norm of a Matrix
![nn](https://github.com/Poovarasu8/Norm-of-a-matrix/assets/155505954/6a49e3b1-fad0-48af-b8ff-625b4c5a412f)


### Infinity Norm of a Matrix

![oo](https://github.com/Poovarasu8/Norm-of-a-matrix/assets/155505954/f464438c-2da8-40d6-bfdf-bc28f690b681)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
