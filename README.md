# Task2-QISKIT
The code uses following approach for finding the missing value:

step 1: find the maximum value of list. Let´s call it m
        
step 2: missing value = m*(m+1)/2 - (sum of elements)

For the step 2, the code uses quantum algorithm for addition of two integers. The alogirthm consists of 6 qbits (3 qbits for each integer), and 3 classical bits. Therefore, the code can only work on list with integers less than 8.

The quantum algorithm is basic and needs further improvement for increasing the accuracy
