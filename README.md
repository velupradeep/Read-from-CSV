# Read-from-CSV

## AIM:AIM:
To write a python program for reading content from a CSV file


## ALGORITHM:
### Step 1:Import pandas as pd
### Step 2:Read the CSV file using read_csv method.
### Step 3:Use head and tail method to get the required contents from the file.
### Step 4:Use len() method to get the number of rows and columns.
### Step 5:Print the output

## PROGRAM:
```
# Developed by: PREM.R
# Register Number: 23002486
import pandas as pd
df = pd.read_csv('pandascsv.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```

## OUTPUT:
![Screenshot 2023-12-25 224228](https://github.com/velupradeep/Read-from-CSV/assets/150329341/6dd57f07-94a9-41ae-81d8-a2a0e1a04ef8)


## RESULT:
thus the output got successfully.
