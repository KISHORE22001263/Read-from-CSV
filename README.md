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
Use len() method to get the number of rows and columns
### Step 5:
Print the output
## PROGRAM:
```
program to read the csv file
name:KISHORE.B
REG.NO:212222110020
import pandas as pd
df=pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("rows",df.axes[0])
print("columns",df.axes[1])
print("no. of rows",len(df.axes[0]))
print("no. of columns",len(df.axes[1]))
```
## OUTPUT:
![Screenshot from 2023-06-10 13-37-10](https://github.com/KISHORE22001263/Read-from-CSV/assets/121484538/df70d486-3521-4f6f-9cea-35dfc72134a5)


## RESULT:
Thus a python program is written to read the contents of a CSV file.
