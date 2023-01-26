# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file

## ALGORITHM:
 Step 1: Import pandas as pd.
 
 Step 2: Read the CSV file using read_CSV method.
 
 Step 3: Use head and tail method to get the required contents from the file.
 
 Step 4: Use len() method to get number of rows and columns.
 
 Step 5: Print the output.

## PROGRAM:
```
#To write a python program for reading content from a csv file.
#Developed by: Archana.k
#Register Number: 22009150

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("rows",len(df.axes[0]))
print("columns",len(df.axes[1]))
```
## OUTPUT:
```
Developed by:Archana.k
Register number:22009150
```
![Screenshot 2023-01-26 204538](https://user-images.githubusercontent.com/118708624/214873574-e8b72217-708e-4c78-ae59-d9755a165fde.png)

## RESULT:
Thus a python program is written to read the contents of a CSV file.
