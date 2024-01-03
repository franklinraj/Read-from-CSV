# Read-from-CSV

## AIM:
program to read contents from a csv file

## ALGORITHM:
### Step 1: 
create a csv file named nba.csv 
### Step 2:
now open the file using open()
### Step 3:
import pandas module to access the program
### Step 4:
now the information in the file is been read 
### Step 5:
readed text been displayed 

## PROGRAM:
```
# program to read contents from a csv file
# developd by : franklin raj G
# register no:23001518

import pandas as pd
df=pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail(5))
print("Number of rows:",len(df.axes[0]))
print("number of columns:",len(df.axes[1]))
```
## OUTPUT:
![Screenshot 2024-01-03 134855](https://github.com/franklinraj/Read-from-CSV/assets/148993740/7618b108-6ff4-47de-9022-88db00b0832b)

## RESULT:
program is successful and output is been execueted
