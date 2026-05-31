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
# Register No: 212225230012
# Developed By: ALAPATI KRANTHI KIRAN
```

```
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=eval(input())
b=np.linalg.norm(a,1)
print(f"{b:.2f}")
```

```
# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=eval(input())
b=np.linalg.norm(a,2)
print(f"{b:.2f}")
```

```
# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=eval(input())
b=np.linalg.norm(a,np.inf)
print(f"{b:.2f}")
```
## Output:
### 1-Norm of a Matrix
<img width="419" height="148" alt="image" src="https://github.com/user-attachments/assets/83eac33f-24dc-426a-83f8-bb0d9dffade2" />


### 2-Norm of a Matrix
<img width="373" height="179" alt="image" src="https://github.com/user-attachments/assets/b4b2f856-3f16-4845-818c-a731d6650c40" />


### Infinity Norm of a Matrix
<img width="406" height="145" alt="image" src="https://github.com/user-attachments/assets/c380666e-4784-4b8a-8aae-9dcc988e73a6" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
