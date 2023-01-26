# Read-from-CSV

## AIM:
To develop a python program to read a file rom csv.
## ALGORITHM:
### Step 1:
Import the pandas function as pd.
### Step 2:
Read the file and store it in the variable f.
### Step 3:
Print the head and tail.
### Step 4:
Print the number of rows using the length function(len).
### Step 5:
Print the number of coloumns using the same length function(len).

## PROGRAM:
```
import pandas as pd
df = pd.read_csv('/nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```

## OUTPUT:
![Screenshot (22)](https://user-images.githubusercontent.com/121165996/214908611-5af3f2d9-2a7c-499e-b055-e9e4053bf19c.png)


## RESULT:

Thus the program is successfully executed.
