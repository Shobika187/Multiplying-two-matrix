# Multiplying-two-matrix

## AIM:

To a solutipn by multiplying two arrays using numpy.

## ALGORITHM:

### Step 1:

Import numpy as mp.

### Step 2:

Get a input as integer.

### Step 3:

Append the list using  a for loop.

### Step 4:

Multiply the two list .

### Step 5:

Get the result for multiplication of arrays.

## PROGRAM: 
```
import numpy as np
l1,l2=[],[]
n=int(input())
for i in range(n):
    l1.append(int(input()))
for i in range(n):
    l2.append(int(input()))
value1=np.array(l1)
value2=np.array(l2)
result=value1*value2
print("Product of two arrays is:",result)
```
## OUTPUT:
![Output](.//img4.png)

## RESULT:

Product of two array is successfully founded using numpy.

