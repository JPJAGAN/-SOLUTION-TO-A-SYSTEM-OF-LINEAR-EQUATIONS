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
#Program to find the solution for the given linear equations.
#Developed by:Jagan J P 
#RegisterNumber:212224230099


a1,b1,c1,d1 = 5,-3,-10,-9
a2,b2,c2,d2 = 2,2,-3,4
a3,b3,c3,d3 = -3,-1,5,-1

D = a1*(b2*c3-b3*c2) - b1*(a2*c3-a3*c2) + c1*(a2*b3-a3*b2)

Dx = d1*(b2*c3-b3*c2) - b1*(d2*c3-d3*c2) + c1*(d2*b3-d3*b2)
Dy = a1*(d2*c3-d3*c2) - d1*(a2*c3-a3*c2) + c1*(a2*d3-a3*d2)
Dz = a1*(b2*d3-b3*d2) - b1*(a2*d3-a3*d2) + d1*(a2*b3-a3*b2)

x = Dx//D
y = Dy//D
z = Dz//D

print("[" + str(x) + ".  " + str(y) + ". " + str(z) + ".]")
```
<img width="1243" height="511" alt="image" src="https://github.com/user-attachments/assets/576917aa-b902-4978-851b-f79534e3ed62" />

## Output:
<img width="1300" height="298" alt="image" src="https://github.com/user-attachments/assets/e4991030-87aa-46b0-baa0-fe3a61e9e754" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program
