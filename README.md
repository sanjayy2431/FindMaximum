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
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large




```

ii)	# To find the maximum marks using the list method max().
```
def max_marks(marks):
    large = max(marks)
    return large




```

iii) # To find the maximum marks without using builtin functions.
```
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max




```



## Output:
## SORT()
![Screenshot 2024-03-23 110208](https://github.com/sanjayy2431/FindMaximum/assets/149365143/8df6c6fd-f726-43fb-8f91-65c769d9003a)


## MAX()
![image](https://github.com/sanjayy2431/FindMaximum/assets/149365143/5dee249c-c520-45d8-85b7-f8c46f015ea3)



## BUILT-IN FUNCTION()
![Screenshot 2024-03-23 111441](https://github.com/sanjayy2431/FindMaximum/assets/149365143/136f4a70-9a5a-457f-acb0-e8b0a89fd685)






## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
