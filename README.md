# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare the lists from each linear equations and assign in np.array().
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program.
## Program:
```python
#Program to find the solution for the given linear equations.
#Developed by: Mohammed Faizal.J
#RegisterNumber:22003412
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
b=np.array([-9,4,-1])
rank=np.linalg.solve(A,b)
print(rank)
```
## Output:
![WhatsApp Image 2023-01-03 at 2 22 21 PM](https://user-images.githubusercontent.com/111619160/210325646-7caadaae-145a-4634-86a5-568a385f87cc.jpeg)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program.

