# Read-from-CSV

## AIM:

To write a python program for reading the csv file content.
## ALGORITHM:
### Step 1:
Load the CSV into a DataFrame.
### Step 2:

Print the number of contents to be displayed using df.head().
### Step 3:

The number of rows returned is defined in Pandas option settings.
### Step 4:

Check your system's maximum column with the pd.options.display.max_column statement.
### Step 5:

Increase the maximum number of rows to display the entire DataFrame.
## PROGRAM:
```
## Developed by:SRINIDHI SENTHIL
## REGISTER NUMBER: 22001408

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("rows",len(df.axes[0]))
print("columns",len(df.axes[1]))
```

## OUTPUT:

![image](https://user-images.githubusercontent.com/121373170/214645167-8156b7a9-c467-4ccb-b506-19cd4ef4ff36.png)


## RESULT:
Thus the program is written to read the csv file.
