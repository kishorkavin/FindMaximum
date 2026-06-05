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

def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python

def max_marks(marks):
    large = max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python

def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max        


```



## Output:
<img width="1027" height="387" alt="image" src="https://github.com/user-attachments/assets/266b7129-b58b-481f-8ec6-2085f274ff6e" />
<img width="1005" height="380" alt="image" src="https://github.com/user-attachments/assets/12afda41-e965-4aea-b1ad-46ec681bd8cd" />
<img width="1020" height="396" alt="image" src="https://github.com/user-attachments/assets/b302d0b0-5a39-4635-975e-97d15091f18d" />


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
