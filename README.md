## Simple csv creator in python using pandas library

### Example usage

```python
csv = CSV("expense.csv")
csv.initializeCsv(["date", "amount", "description"])
csv.addEntry("10-02-2024", 55, "Book")
csv.addEntry("15-03-2024", 23, "Movie")
# Entered record added successfully
```

```python
csv = CSV("expense.txt")
# throws error: Not a valid csv file name
```

```python
csv = CSV("expense.csv")
csv.initializeCsv(["date", "amount", "description"])
csv.addEntry("10-02-2024", 55)
# throws error: The number of columns and the data does not match
```
