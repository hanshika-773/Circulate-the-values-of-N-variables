# Date: 
# Ex.No.2: Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: using the keyword 'def' create function.
### Step 2: name the function as 'circulate'.
### Step 3:  Get the value from the user for the number of rotation
### Step 4: Convert the index input to an integer.
### Step 5: Using the slicing concept rotate the list
### Step 6: Print the resulting list after the circular shift.
## Program:
```
def circulate():
    a=eval(input())
    b=int(input())
    l=a[b:]+a[:b]
    print("After circulating the values are:",l)
```
## Output:
![Screenshot 2024-08-28 225540](https://github.com/user-attachments/assets/cb6dcb8f-32db-4f23-9f44-b0f61a73ff5f)

## Result: Thus, circulating the n variables using function concept are successfully executed.
