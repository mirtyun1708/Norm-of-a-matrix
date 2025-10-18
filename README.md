# Norm of a matrix
## Developed By:Mirtyunjay.S
## Register Number:212224040190
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
# Register No:212224040190
# Developed By:Mirtyunjay .S
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
<img width="1229" height="348" alt="Screenshot 2025-10-18 080253" src="https://github.com/user-attachments/assets/44153d2b-1f9b-4e30-aabd-53e9eca58813" />


### 2-Norm of a Matrix
<img width="1221" height="379" alt="Screenshot 2025-10-18 080309" src="https://github.com/user-attachments/assets/23e2673a-9b37-4fdc-9915-d09e11df500b" />


### Infinity Norm of a Matrix
<img width="1218" height="337" alt="Screenshot 2025-10-18 080321" src="https://github.com/user-attachments/assets/a454b45b-7cdf-457f-9c23-a7620701f9fe" />

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
