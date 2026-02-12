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
# Register No:212225220051
# Developed By:Kervin.S
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)





```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>
<img width="1249" height="852" alt="Screenshot 2026-02-12 195128" src="https://github.com/user-attachments/assets/f74fe2e1-ed62-4c11-8bc1-22e3d34c3c16" />

### 2-Norm of a Matrix
<br>
<br>
<br>
<img width="1206" height="827" alt="Screenshot 2026-02-12 195142" src="https://github.com/user-attachments/assets/a218601e-640d-4c40-8d4a-aca8fd451926" />

### Infinity Norm of a Matrix
<br>
<br>
<br>
<img width="1221" height="823" alt="Screenshot 2026-02-12 195154" src="https://github.com/user-attachments/assets/beddd48e-4673-401e-be2b-3a486c26dedd" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
