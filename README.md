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
Developed by:Nishanth J 
RegisterNumber:23007929
'''
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large 



```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by:Nishanth J 
RegisterNumber:23007929
'''
def max_marks(marks):
    large = max(marks)
    return large 



```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by:Nishanth J 
RegisterNumber:23007929
'''
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i>max:
            max=i
    return max        


```
## Sample Input and Output


## Output:
![Screenshot 2023-12-31 211759](https://github.com/Nishanth-018/FindMaximum/assets/149347651/4874cdf6-823f-4381-be77-defd04b3cfdb)
![Screenshot 2023-12-31 212352](https://github.com/Nishanth-018/FindMaximum/assets/149347651/7e7e449c-6bb8-43d2-a99d-47ba2bd29fef)
![Screenshot 2023-12-31 212523](https://github.com/Nishanth-018/FindMaximum/assets/149347651/7a4e91ee-b872-44ea-801d-e2bfd46b59ad)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
