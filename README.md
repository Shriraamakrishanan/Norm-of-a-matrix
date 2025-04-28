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
Register No: 212224220100
Developed By: Shri Raama Krishanan J
```
# 1-Norm of a Matrix
![Screenshot 2025-04-28 124257](https://github.com/user-attachments/assets/c9a62caa-9789-45dc-8597-eb6d0a6f6c5d)
```python
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_matrix="{:.2f}".format(ans)
print(norm_matrix)

```
# b2-Norm of a Matrix
![Screenshot 2025-04-28 124341](https://github.com/user-attachments/assets/8040fb5e-0279-478c-9e60-89f2354dfd90)
```python
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_matrix="{:.2f}".format(ans)
print(norm_matrix)
```
# Infinity Norm of a Matrix
![Screenshot 2025-04-28 124749](https://github.com/user-attachments/assets/f9653498-57d3-45ae-bfa6-839a22903aee)
```python
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_matrix="{:.2f}".format(ans)
print(norm_matrix)
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2025-04-28 124913](https://github.com/user-attachments/assets/db8afe7c-a7ce-4f1d-adf1-2f91db68a067)
### 2-Norm of a Matrix
![Screenshot 2025-04-28 125039](https://github.com/user-attachments/assets/5a1c9166-86ca-4fe6-8780-863f75e39d20)
### Infinity Norm of a Matrix
![Screenshot 2025-04-28 125115](https://github.com/user-attachments/assets/6ede117a-bcec-4cb4-a6f4-343fa19f9d3a)
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
