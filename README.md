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
### ```Python
### Register No:26010139
### Developed By: Keerthi.v
### 1-Norm of a Matrix
### import os 
### os.environ["OPENBLAS_NUM_THREADS"]="1"
### import numpy as np
### mat=np.array(eval(input()))
### ans=np.linalg.norm(mat,1)
### norm_of_matrix="{:2f}".format(ans)
### print(norm_of_matrix)




### 2-Norm of a Matrix
### Developed by: keerthi.V
### RegisterNumber: 26010139
### import os
### os.environ["OPENBLAS_NUM_THREADS"]="1"
### import numpy as np
### mat=np.array(eval(input()))
### ans=np.linalg.norm(mat,2)
### norm_of_matrix="{:.2f}".format(ans)
### print(norm_of_matrix)




### 3-Infinity Norm of a Matrix
### Developed by: keerthi.V
### RegisterNumber: 26010139
### import os
### os.environ["OPENBLAS_NUM_THREADS"]="1"
### import numpy as np
### mat=np.array(eval(input()))
### ans=np.linalg.norm(mat,np.inf)
### norm_of_matrix="{:.2f}".format(ans)
### print(norm_of_matrix)
### ```
## Output:
### 1-Norm of a Matrix
<img width="967" height="856" alt="image" src="https://github.com/user-attachments/assets/fc13ee0e-92bf-4711-9580-a4d97ef62239" />

### 2-Norm of a Matrix
<img width="907" height="862" alt="image" src="https://github.com/user-attachments/assets/ffd5fc0c-9c2d-4c87-a94a-be1cc0cab549" />


### Infinity Norm of a Matrix
<img width="811" height="852" alt="image" src="https://github.com/user-attachments/assets/f3580dc0-c346-4259-a763-f05fb5d731d4" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
