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
Developed by: Adhithiyan.k
RegisterNumber: 22001999
'''
def max_marks(marks):
    marks.sort()
    large = marks [-1]
    return large



```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: Adhithiyan.k
RegisterNumber: 22001999
'''
def max_marks(marks):
    large = max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: Adhithiyan.k
RegisterNumber: 22001999
'''
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max


```


## Output:

![Screenshot_20230128_082823](https://user-images.githubusercontent.com/121029258/215273944-21b1dd20-075a-4b3d-ac36-3d39a24da244.png)
![Screenshot_20230128_082844](https://user-images.githubusercontent.com/121029258/215273946-a53c2236-348a-40e2-aa5a-3da04c2b2b80.png)
![Screenshot_20230128_082905](https://user-images.githubusercontent.com/121029258/215273949-c418c30c-741f-412c-988c-8496614e8b34.png)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
