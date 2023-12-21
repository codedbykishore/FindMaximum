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
Developed by: Kishore B
RegisterNumber: 23013723
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
Developed by: Kishore B
RegisterNumber: 23013723
'''
def max_marks(marks):
    a=max(marks)
    return a
```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: Kishore B
RegisterNumber: 23013723
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max

```
## Sample Input and Output
### i)
![Screenshot 2023-11-29 172538](https://github.com/Prajin19/FindMaximum/assets/144979377/86dd3a47-85bb-454d-a3db-7e4d9e47c979)
### ii)
![Screenshot 2023-11-29 172626](https://github.com/Prajin19/FindMaximum/assets/144979377/0f759028-069b-4cff-bd60-4bec57df8549)
### iii)
![Screenshot 2023-11-29 172715](https://github.com/Prajin19/FindMaximum/assets/144979377/e1a29ecb-c4b7-4929-a15a-bc84f81e705a)

## Output:
### i)
![Screenshot from 2023-12-21 21-42-06](https://github.com/codedbykishore/FindMaximum/assets/147139122/d7ee27db-4dbb-4cb6-ac8e-f29ea1fe7bc0)
### ii)
![Screenshot from 2023-12-21 21-42-51](https://github.com/codedbykishore/FindMaximum/assets/147139122/ee098002-db1f-46b8-9b74-aaace3ebbb8a)
### iii)
![Screenshot from 2023-12-21 21-43-23](https://github.com/codedbykishore/FindMaximum/assets/147139122/f203e7ef-5644-47b5-b79e-7854fe281bb0)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
