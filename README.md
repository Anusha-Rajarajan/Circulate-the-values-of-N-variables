# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
Get value from the user for calculation 
### Step 2:
Assign the values
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5:
Print both the values it would be circulated 
### Step 6:
End the program 
## Program:
~~~
#Program to circulate N values.
#Developed by: Anusha R
#RegisterNumber: 21005561
def circulate():
    list1=[10,20,30,40,50,60]
    n=int(input())
    list1=list1[n:]+list1[:n]
    print("After circulating the values are:",list1)
~~~
## Output:
![output](.//cir.png)
## Result:
Thus the circulating of values are successfully executed
