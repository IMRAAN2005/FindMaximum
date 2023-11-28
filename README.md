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
Developed by: SHAIK MAHAMMAD IMRAAN
RegisterNumber: 23011682
'''
def max_marks(marks):
    #Write your code here
    marks.sort()
    large=marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: SHAIK MAHAMMAD IMRAAN
RegisterNumber: 23011682
'''
def max_marks(marks):
    # write your code here
    large=max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: SHAIK MAHAMMAD IMRAAN
RegisterNumber: 23011682
'''
def max_marks(marks):
    # write your code here
    large=max(marks)
    return large


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
i)![image](https://github.com/IMRAAN2005/FindMaximum/assets/149347407/62ed6624-242d-4207-aa52-8713f9db1415)
ii)![image](https://github.com/IMRAAN2005/FindMaximum/assets/149347407/6a4781f9-3d7f-4100-8e12-72a9ce43b09b)
iii)![image](https://github.com/IMRAAN2005/FindMaximum/assets/149347407/a27399f4-142c-4a66-b4ee-a69d79dcbcef)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
