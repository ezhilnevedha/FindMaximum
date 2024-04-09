## NAME: EZHIL NEVEDHA.K
## REGISTER NUMBER:212223230055
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
DEVELOPED BY: EZHIL NEVEDHA.K          
REGISTER NUMBER:212223230055  
(i)	# To find the maximum of marks using the list method sort.
```
Python
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```


(ii)	# To find the maximum marks using the list method max().
```
Python
def max_marks(marks):
    large=max(marks)
    return large
```

(iii) # To find the maximum marks without using builtin functions.
```
Python
def max_marks(list1):
    max_num=list1[0]
    for i in list1:
        if i>max_num:
            max_num=i
    return max_num
```




## Output:
(i)	# To find the maximum of marks using the list method sort.
![alt text](<Screenshot 2024-04-09 173711.png>)
(ii)	# To find the maximum marks using the list method max().
![alt text](<Screenshot 2024-04-09 173833.png>)
(iii) # To find the maximum marks without using builtin functions.
![alt text](<Screenshot 2024-04-09 173932.png>)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
