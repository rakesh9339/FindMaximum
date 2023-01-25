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
Developed by:Rakesh J.S 
RegisterNumber:22009339 
```
i)	# To find the maximum of marks using the list method sort.

Program to mark the maximum of marks using the list method sort
Developed by: Rakesh J.S
RegisterNumber: 22009339
'''
def max_marks(marks):
    #Write your code here
    marks.sort()
    large = marks[-1]
    return large


ii)	# To find the maximum marks using the list method max().''' 
Program to find the maximum marks using the list method max().
Developed by: Rakesh J.S
RegisterNumber: 22009339
'''
def max_marks(marks):
    # write your code here
    large = max(marks)
    return large
    
iii) # To find the maximum marks without using builtin functions.

def max_marks(list1):
''' 
Program to find the maximum marks using the list method max().
Developed by: Rakesh J.S
RegisterNumber: 22009339
'''
def max_marks(marks):
    # write your code here
    large = max(marks)
    return large
           
```
## Sample Input and Output:
![](RN.png)

## Output:
i) To find the maximum of marks using the list method sort.
![](RN1.png)

ii)	To find the maximum marks using the list method max().
![](RN2.png)

iii)To find the maximum marks without using builtin functions.
![](RN3.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
