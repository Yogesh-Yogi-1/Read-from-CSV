# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1:
Import pandas as pd
### Step 2:
Read the csv file using read_csv method.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns.
### Step 5:
Print the output.
## PROGRAM:
```
\*
# Program to read contents from a csv file
# Developed by: V. Yogesh
# Register no: 212223230250
\*
import pandas as pd
df=pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail(5))
print("Number of rows: ",len(df.axes[0]))
print("Number of columns: ",len(df.axes[1]))
```
## OUTPUT:
![Screenshot 2024-01-02 222925](https://github.com/Yogesh-Yogi-1/Read-from-CSV/assets/148514598/d53ef322-dbf9-478e-9682-e262e3715b13)

## RESULT:
