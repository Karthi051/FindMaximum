# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```
''' 
Program to mark the maximum of marks using the list method sort
Developed by: KARTHI KEYAN K
RegisterNumber: 23013936
'''
def max_marks(marks):
    c=sorted(marks)
    m=c[-1]
    return m
```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: KARTHI KEYAN K
RegisterNumber: 23013936
'''
def max_marks(marks):
    # write your code here
    c=max(sorted(marks))
    return c
```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: KARTHI KEYAN K
RegisterNumber: 23013936
'''
def max_marks(list1):
    # write your code here
    
    max_marks=list1[0]
    for i in list1:
        if i>max_marks:
            max_marks = i
    return max_marks
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![image](https://github.com/Karthi051/FindMaximum/assets/148327224/5f573dc0-472e-4249-b46b-759075ced41e)

![image](https://github.com/Karthi051/FindMaximum/assets/148327224/433bb153-3a11-4887-ac6f-c49d9fc293a5)

![image](https://github.com/Karthi051/FindMaximum/assets/148327224/0cb8b7ca-bb01-43de-9f5c-01228b7fa243)






## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
