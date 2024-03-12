# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Define a function circulate() to perform list rotation.
### Step 2: 
Receive the input list from the user.
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
 Concatenate the rotated sublist with the sublist starting from index 0 to m-1.
### Step 6: 
Print the rotated list.

## Program:
```
def circulate():
    l= eval(input())
    m= int(input())
    l= l[m: ]+l[ :m]
    print("After circulating the values are:",l)
```
## Output:
![image](https://github.com/Sajetha13/Circulate-the-values-of-N-variables/assets/138849316/f6945aa8-96ea-4af4-85aa-3def63aebef8)

## Result:
Thus the circulating the n variables is succesfully completed
