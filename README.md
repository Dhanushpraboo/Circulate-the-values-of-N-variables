# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Define the function circulate
### Step 2: 
Assign the value of L for circulation
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print the values after Circulation
### Step 6: 
End the program
## Program:
~~~
def circulate():
    L= [10, 20,30,40,50,60] 
    n= int(input()) 
    l= L[n:]+L[:n]
    print("After circulating the values are:",l)
~~~

## Output:
![Ex_2](ex_2.png)

## Result:
