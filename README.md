# Exp-6-Read from CSV

## AIM:
Python Program to read read contents from csv file
## ALGORITHM:
1. Import and load
2. Peek at data
3. Check dimensions
4. Print the number of rows and columns in the DataFrame.


## PROGRAM:
~~~
# Program to read read contents from csv file
# Developed by : P.LOKNAATH
# Register Number : 212223240080

import pandas as pd
df=pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail(5))
print("Number of rows: ",len(df.axes[0]))
print("Number of columns: ",len(df.axes[1]))

~~~
## OUTPUT:
![1](https://github.com/Loknaath-sec/Read-from-CSV/assets/145742558/27100999-0b86-4ac2-8ea3-27e8c9d480dc)
![2](https://github.com/Loknaath-sec/Read-from-CSV/assets/145742558/ab11ce2e-9c00-49f0-8354-8c04b7922a6e)

## RESULT:
Thus the python program to read read contents from csv file is executed.
