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
Developed by: Migal G Arunadann 
RegisterNumber: 212222110048
'''
def max_marks(marks):
    marks.sort()
    max=marks[-1]
    return max



```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: Migal G Arunadann
RegisterNumber: 212222110048
'''
def max_marks(marks):
    max_marks=max(marks)
    return max_marks



```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: Migal G Arunadann
RegisterNumber: 212222110048
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max



```

## Output:

# To find the maximum of marks using the list method sort.
![image](https://github.com/Migaleyy/FindMaximum/assets/118262199/5f03bb49-af94-4bd6-9e05-3cea05adf153)

# To find the maximum marks using the list method max().
![image](https://github.com/Migaleyy/FindMaximum/assets/118262199/f3be7400-c364-444b-93e7-14a9abde8f47)

# To find the maximum marks without using builtin functions.
![image](https://github.com/Migaleyy/FindMaximum/assets/118262199/c3d944bd-0834-48de-905b-fcfab8a6aff3)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
