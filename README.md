# Multiplying-two-matrix

## AIM:
Write a python program to multiply two arrays using numpy

## ALGORITHM:

### Step 1:
Import numpy library using import statement.
### Step 2:
Create two empty lists and use input() method to find the number of elements to add in each list.
### Step 3:
Initiate a for loop and add elements to the list using input() and append() method.
### Step 4:
Create a 3rd empty list and append the product of each element in the first two lists as its elements.
### Step 5:
Convert the final 3rd list to an array using np.array() method and display the result.

## PROGRAM: 
```
'''
Program to multiply two arrays using numpy
Developed by: M.RAJESHKANNAN
RegisterNumber: 21500434
'''

import numpy as np
n=int(input())
l1,l2=[],[]
for i in range (n):
        l1.append(int(input()))
for i in range (n):
        l2.append(int(input()))
arr=np.zeros((n))
l3=[]
for i in range (n):
    l3.append(l1[i]*l2[i])
arr=np.array(l3)
print("Product of two arrays is:",arr)
```

## OUTPUT:

![Screenshot 2022-02-11 232123](https://user-images.githubusercontent.com/93901857/153643491-108b92e1-cc0c-4bc8-988f-b259947e08b4.jpg)

## RESULT:
Thus the python program to multiply two arrays using numpy is successfully executed.

