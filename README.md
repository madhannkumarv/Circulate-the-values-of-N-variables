[# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
Start the program.
### Step 2: 
Read the number of variables n from the user.
### Step 3: 
Read n values and store them in a list.
### Step 4: 
Define a function to circulate the variables

### Step 5: 
Call the function and store the circulated result.
### Step 6: 
Display the circulated variables and stop the program.
## Program:
```
def circulate():
    list1=eval(input())
    count=int(input())
    for i in range(count):
        list1.append(list1[0])
        list1.pop(0)
    print("After circulating the values are:",list1)
    return
```
## Output:
<img width="1277" height="488" alt="image" src="https://github.com/user-attachments/assets/9b0dbcaf-4bb0-44ca-87c9-584650ae7a24" />

## Result:
Thus the python program to circulate the n variables using function concept is done and executed.
](https://github.com/madhannkumarv/Swapping-two-values)
