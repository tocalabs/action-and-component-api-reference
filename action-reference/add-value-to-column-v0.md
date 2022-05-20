# Add Value to Column v0

### Info

- Category: Table
- Requires Nested actions: False


### Description
Add a value at the next available space in a column, this will insert the value at the first available empty cell in the specified column or it will create a new row at the end of the column if necessary. This will modify the original table in place rather than return a new table.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Table | variable |  | True |  |
| Column to add value to | text |  | True |  |
| Value to add | text |  | True |  |
| Timeout (ms) | number |  | False | 30000 |
| Error on Timeout | checkbox |  | False | True |
| Fail On Error | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns
This action returns no results.

---