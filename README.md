# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the list of values from the user

### Step 2: 
Get the values from the user for the numberof rotation

### Step 3: 
declare a function starting with a keyword "def"

### Step 4: 
within the function print the output statement

### Step 5: 
using slicing concept rotate the list

### Step 6: 
display the output

## Program:
```
#Program to circulate N values.
#Developed by:jeevitha S 
#RegisterNumber:212222100016
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
    
```
## Output:
![Screenshot (122)](https://user-images.githubusercontent.com/123623197/234817967-eed7ca7c-3a7c-4f50-a7e4-e9ce4f16a690.png)


## Result:
cirlate n variables created successfully.
