# Exporting and Importing Data

> [!IMPORTANT]
> Users can export their calculation history to a file and restore it later.

## Exporting Calculations
To save calculation history:
```sh
calculator.exe export results.txt
```
This creates a text file with past calculations.

## Importing Data
To load calculations from a CSV file:
```sh
calculator.exe import data.csv
```
Ensure the CSV format matches:
```csv
operation,value1,value2,result
add,5,3,8
multiply,4,2,8
```

## Next Steps
For detailed calculator usage, see [Basic Operations](../working-with-calculations/basic-operations.md).
```