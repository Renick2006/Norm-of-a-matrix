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
# Register No: 24900741
# Developed By: Renick Fabian Rajesh
# 1-Norm of a Matrix
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,1)
print(result)



# 2-Norm of a Matrix
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,2)
print(round(result,2))



# Infinity Norm of a Matrix
import  numpy as np
a=np.array(eval(input()))
result=np.linalg.norm(a,np.inf)
print(result)




```
## Output:
### 1-Norm of a Matrix
<br>![Screenshot 2024-12-02 131314](https://github.com/user-attachments/assets/55b03edd-2137-4c8b-9f24-9937f912dc81)

<br>
<br>

### 2-Norm of a Matrix
<br>![Screenshot 2024-12-02 131350](https://github.com/user-attachments/assets/c73d0b96-744d-45d7-bbd4-ce39a74932df)

<br>
<br>

### Infinity Norm of a Matrix
<br>![Screenshot 2024-12-02 131413](https://github.com/user-attachments/assets/be01f025-70a3-499a-89e4-44f023e2d1fb)

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
