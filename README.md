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
List method sort:
![image](https://github.com/Yeshwanthperumal/FindMaximum/assets/119476088/fc71bbe4-748e-4460-a97c-639d8a149a1b)

List method max:
![image](https://github.com/Yeshwanthperumal/FindMaximum/assets/119476088/9ba75eaa-b776-4d70-918b-08bbde801f29)

Builtin functions:
![image](https://github.com/Yeshwanthperumal/FindMaximum/assets/119476088/c13d731d-5f28-47a7-a6c2-4b7af0eb1fcc)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
