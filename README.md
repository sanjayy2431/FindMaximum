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
#Program to mark the maximum of marks using the list method sort
#Developed by: V.sanjay
#Register number: 212223230188

def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large




```

ii)	# To find the maximum marks using the list method max().
```
#Program to find the maximum marks using the list method max()
#Developed by: V.sanjay
#Regsiter number: 212223230188

def max_marks(marks):
    large = max(marks)
    return large




```

iii) # To find the maximum marks without using builtin functions.
```
#Program to find the maximum marks without using builtin functions
#Developed by: V.sanjay
#Register number: 212223230188

def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max




```



## Output:
## SORT()
![image](https://github.com/sanjayy2431/FindMaximum/assets/149365143/9a3bee66-0a46-4d2e-a84f-4be47e436a88)



## MAX()
![image](https://github.com/sanjayy2431/FindMaximum/assets/149365143/2f7032a8-3e3c-496a-bd73-fcede42c9452)



## BUILT-IN FUNCTION()
![image](https://github.com/sanjayy2431/FindMaximum/assets/149365143/49f1e653-7f71-4162-9a04-b5362376b2c7)






## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
