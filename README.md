# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
### Step 2: 
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
### Step 6: 
## Program:
```python
def circulate():
    values=eval(input())
    n=int(input())
    for i in range(n):
        temp=values.pop(0)
        values.append(temp)
    print("After circulating the values are:",values)
```

## Output:
![Screenshot 2024-03-09 090321](https://github.com/Samakas/Circulate-the-values-of-N-variables/assets/154731670/5eb6c1c1-4f60-4166-95c5-3e4650203a8b)
![Screenshot 2024-03-09 090337](https://github.com/Samakas/Circulate-the-values-of-N-variables/assets/154731670/db0c7f4d-192e-469f-a0ef-76cb940a60eb)

## Result:
