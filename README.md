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
```Python
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
```Python
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
```Python
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
![image](https://github.com/etjabajasphin/FindMaximum/assets/148327224/e46b4963-edbb-46f3-92fb-3350cd88a444)
![image](https://github.com/etjabajasphin/FindMaximum/assets/148327224/5fb2de9b-bd7c-40fc-b4e8-1979c8243b0f)
![image](https://github.com/etjabajasphin/FindMaximum/assets/148327224/204436a9-4de0-4795-93ea-5b9359335526)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
