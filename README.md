# Read-from-CSV

## AIM: 
To write a program for reading the csv file content.

## ALGORITHM:
### Step 1:
Load the CSV into a DataFrame
### Step 2:
Print the number of contents to be displayed using df.head().
### Step 3:
The number of row returned is defined in pandas option settings.
### Step 4:
Check your systems maximun column with the pd.options.display.max_columun statement.
### Step 5:
Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:
```python
#Developed by : HARIHARAN A
#Registered number :22001891
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head(10))
print(df.tail())
print("Column",len(df.axes[0]))
print("Row",len(df.axes[1]))

```

## OUTPUT:
![image](https://user-images.githubusercontent.com/120353431/214838538-21b08329-ef38-470b-91b3-dd9eb0f2a16f.png)


## RESULT: 
Thus the program executed successfully for read csv file.
