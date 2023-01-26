# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1:
Start the python.
### Step 2:
Import pandas.
### Step 3:
Mention the CSV file which is to be read.
### Step 4:
Read the contents of the CSV file using df.read function.
### Step 5:
End the program.
## PROGRAM:
```
#Devloped By:Yuvarani T
#Ref no:22009033
import pandas as pd
df = pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("column", len(df.axes[0]))
print("rows", len(df.axes[1]))
```
## OUTPUT:
![CSV](https://user-images.githubusercontent.com/121418522/214825922-9aa9ec62-3d34-4c5f-979d-256f35633838.png)

## RESULT:
A python program to read data from CSV files has been created successfully.
