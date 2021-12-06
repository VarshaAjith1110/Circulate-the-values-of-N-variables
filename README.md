# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
Define a function called circulate to cirulate the n variables. 
### Step 2: 
The function will circulate the n variables as per the input given.
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Print the circulated output as per the input given.
### Step 6:
End the program. 
## Program:
```
#Program to circulate N values.
#Developed by: Varsha Ajith 
#RegisterNumber :21500246
def circulate():
    num1=[10,20,30,40,50,60]
    n=int(input())
    cir=num1[n:]+num1[:n]
    print("After circulating the values are:",cir) 
```

## Output:
![](circulate_01.png)
## Result:
Thus, a python program to circulate the n variables using function concept is executed successfully.
