# Algorithm for QR Decomposition
## Aim:
To implement QR decomposition algorithm using the Gram-Schmidt method.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Intialize the matrix Q and u
2.	The vector u and e is given by

    ![eqn1](./ex4.jpg)

    ![eqn2](./ex6.jpg)

    ![eqn3](./ex3.jpg)

3.	Obtain the Q matrix   
    ![eqn4](./ex1.jpg)
4.	Construct the upper triangular matrix R
    ![eqn5](./ex2.jpg)



## Program:
```
'''
# 1-norm
Program to find 1-norm of a matrix.
Developed by: Sanchita Sandeep
RegisterNumber: 212224240142
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

#2-norm
'''
Program to find 2-norm of a matrix.
Developed by: Sanchita Sandeep
RegisterNumber: 212224240142
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

#Infinity norm of matrix
'''
Program to find Infinity of a matrix.
Developed by: Sanchita Sandeep
RegisterNumber: 212224240142
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))

```


## Output

![Screenshot 2025-04-22 111517](https://github.com/user-attachments/assets/538f0d19-8228-412a-a14e-ec25bd16126e)
![Screenshot 2025-04-22 111638](https://github.com/user-attachments/assets/f07555e7-c748-4b60-b057-32af572c0787)
![Screenshot 2025-04-22 111805](https://github.com/user-attachments/assets/dea59b00-bb07-4744-ae5b-5ddafaa24231)






## Result
Thus the QR decomposition algorithm using the Gram-Schmidt process is written and verified the result.
