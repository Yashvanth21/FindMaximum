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

## i)	 To find the maximum of marks using the list method sort.
```Python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Yashvanth K
RegisterNumber: 23011613
'''
def max_marks(marks):
    #Write your code here
    marks.sort()
    large=marks[-1]
    return large


```

## ii)	To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: Yashvanth K
RegisterNumber: 23011613
'''
def max_marks(marks):
    # write your code here
    large = max(marks)
    return large


```

## iii) To find the maximum marks without using builtin functions.
```Python

''' 
Program to the maximum marks without using builtin functions.
Developed by: Yashvanth K
RegisterNumber: 23011613
'''
def max_marks(list1):
    # write your code here
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max

```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![Exp 3a 1](https://github.com/Yashvanth21/FindMaximum/assets/144979957/b32c799b-49bd-471d-8c58-6df495c70922)

![Exp 3 a2](https://github.com/Yashvanth21/FindMaximum/assets/144979957/bb72f5c3-2d7e-4896-ad10-791100878d5b)

![Exp 3 a3](https://github.com/Yashvanth21/FindMaximum/assets/144979957/a36a69e9-d3b4-4efe-8b5b-f47571ea7b80)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
