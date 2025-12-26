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
# Register No:25011798
# Developed By:VAIDEESHWARAN G
# 1-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
print(f"{np.linalg.norm(a,1):.2f}")


# 2-Norm of a Matrix
import numpy as np

a=np.array(eval(input())) 
print(f"{np.linalg.norm(a,2):.2f}")



# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input())) 
print(f"{np.linalg.norm(a,np.inf):.2f}") 




```
## Output:
### 1-Norm of a Matrix
<img width="1920" height="1080" alt="Screenshot 2025-12-22 163423" src="https://github.com/user-attachments/assets/fb6e929d-8782-434c-9e22-df74a6493852" />


### 2-Norm of a Matrix

<img width="1920" height="1080" alt="Screenshot 2025-12-22 163432" src="https://github.com/user-attachments/assets/a8b027e7-0c95-48dc-bcb5-3bcc29b85b11" />

### Infinity Norm of a Matrix

<img width="1920" height="1080" alt="Screenshot 2025-12-22 163440" src="https://github.com/user-attachments/assets/c5037f3e-edaa-45a7-8243-410fe6079dc0" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
