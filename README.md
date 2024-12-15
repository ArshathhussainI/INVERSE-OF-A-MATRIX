# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
## Step1 :
Importing numpy as np
## Step 2:
Assigning a variable for storing matrix value
## Step 3:
Using linalg function function to inverse the matrix
## Step 4:
End the program
## Program:
```
import numpy as np

# Define the matrix
matrix = np.array([[1, 0, 3],
                   [-1, 2, -2],
                   [2, 3, -1]])

# Compute the inverse
try:
    inverse_matrix = np.linalg.inv(matrix)
    
    print(inverse_matrix)
except np.linalg.LinAlgError:
    print("The matrix is singular and cannot be inverted.")
```
## Output:
![Screenshot 2024-12-05 184327](https://github.com/user-attachments/assets/90c0b5d6-f9ee-425d-accc-121ffa72b957)

## Result:
Thus the inverse of given matrix is successfully solved using python program

