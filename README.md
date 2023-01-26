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
#Developed by: SAKTHIVEL R
#RegisterNumber: 22009121

def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```
#Developed by: SAKTHIVEL R
#RegisterNumber: 22009121

def max_marks(marks):
    large=max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```
#Developed by:SAKTHIVEL R
#RegisterNumber: 22009121

def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
````
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
1)

![Screenshot from 2023-01-26 17-49-15](https://user-images.githubusercontent.com/120550359/214833871-ae622303-7d32-471c-981a-a99b96dec044.png)

 2)
![Screenshot from 2023-01-26 17-51-15](https://user-images.githubusercontent.com/120550359/214834208-0c95a6f5-67f1-4877-bb9c-a326b2e6586f.png)

3)

![Screenshot from 2023-01-26 17-52-40](https://user-images.githubusercontent.com/120550359/214834247-567bbf25-5636-4bec-8f2f-586aba854fb1.png)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
