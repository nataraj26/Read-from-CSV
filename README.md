# Read-from-CSV

## AIM:
To write a program for reading csv file

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

Increase the maximum number of rows to display the entire DataFrame

## PROGRAM:
```
#Program to read contents from a csv file
#Developed by : NATARAJ KUMARAN
#Register nuumber: 23003973
import pandas as pd
df=pd.read_csv("C:/Users/admin/Downloads/nba.csv")
print(df.head(10))
print(df.tail(5))
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1])) print(df.shape)
```
## OUTPUT:
![image](https://github.com/nataraj26/Read-from-CSV/assets/147514615/40e21560-42f0-42a7-b757-377359659342)


## RESULT:
The program executed succesfull for read CSV file
