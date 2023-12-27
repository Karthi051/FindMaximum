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
1
![image](https://github.com/Karthi051/FindMaximum/assets/148327224/00a323ce-f0be-4592-b8d1-160293d7d587)
2
![image](https://github.com/Karthi051/FindMaximum/assets/148327224/8899b699-9d41-4912-9b92-211bac22aba5)
3
![image](https://github.com/Karthi051/FindMaximum/assets/148327224/2444d34c-0075-49dc-8e85-84a115ccd747)





## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
