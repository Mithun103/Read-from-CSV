# Read-from-CSV
## AIM:
To write a python program for reading content from a CSV file.

## ALGORITHM:
### Step 1:
Import pandas as pd.

### Step 2:
Read the CSV file using read_csv method.

### Step 3:
Use head and tail method to get the required contents from the file.

### Step 4:
Use len() method to get the number of rows and columns.

### Step 5:
Print the output.

## PROGRAM:
```
#Developed by: MITHUN MS
#Reference No: 22008364
import pandas as pd 
f=pd.read_csv('nba.csv')
print(f.head(10))
print(f.tail())
print('Row:',len(f.axes[0]))
print('Col:',len(f.axes[1]))
```
## OUTPUT
![Screenshot_20230126_050736](https://user-images.githubusercontent.com/118344695/214826298-106d1a9d-9e2c-4fa4-86dc-fa7dcce766b2.png)

## RESULT:
Thus a python program is written to read the contents of a CSV file.
