# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
start the program
### Step 2:
Get the input from the user using eval(input()) 
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5:
using concatenation operation display the entire  rotated list   
### Step 6: 
stop the program
## Program:
```
#Program to circulate N values.
#Developed by: Jishnupriyan S
#RegisterNumber: 23008936
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
``` 
## Output:
![image](https://github.com/jishnusankaran/Circulate-the-values-of-N-variables/assets/144979369/1c0b4435-2d7d-48c1-877f-6a7ff33820ef)

## Result:
Thus the python for circulate the values of n varaibles is executed successfully
