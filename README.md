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
Developed by: Arun Kumar B
RegisterNumber: 23004514
'''
def max_marks(marks):
   marks.sort()
   large=marks[-1]
   return large


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: Arun Kumar B
RegisterNumber: 23004514
'''
def max_marks(marks):
   marks.sort()
   large=marks[-1]
   return large



```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: Arun Kumar B
RegisterNumber: 23004514
'''
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i>max:
            max=i
    return max



```
## Sample Input : 
### 1. 
![find question1](https://github.com/Arun2005-create/FindMaximum/assets/138849356/a5c22baf-0290-4ea9-8031-b942105d7ab9)


### 2.
![find question2](https://github.com/Arun2005-create/FindMaximum/assets/138849356/36870d00-988e-4d51-a1eb-7309f834b24f)

### 3.
![find question3](https://github.com/Arun2005-create/FindMaximum/assets/138849356/49c8b9d3-9e07-4e60-b6f8-b139f4a7df86)


## Output:
### 1.
![find answer1](https://github.com/Arun2005-create/FindMaximum/assets/138849356/1a220189-c908-44fb-aacd-de263c4c5eab)


### 2.
![find answer2](https://github.com/Arun2005-create/FindMaximum/assets/138849356/d8e7b432-b29e-4413-8a58-32245e84db7c)


### 3.
![find answer3](https://github.com/Arun2005-create/FindMaximum/assets/138849356/c00c19a5-198b-423a-b849-a7b52b04f90e)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
