# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:

```
a1, b1, c1 = 1, 3, 5 
a2, b2, c2 = 2, 5, - 3
D = a1*b2-a2*b1
Dx = c1 * b2 - c2 * b1 
Dy = a1 * c2 - a2 * c1
x = Dx / D 
y = Dy / D
print(f"[{x:.0f}.  {y:.0f}.]")

```

## Output:

<img width="1492" height="966" alt="image" src="https://github.com/user-attachments/assets/0e7c8303-b8a7-4622-ba47-62654ab11bd2" />


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

