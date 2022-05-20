# Add Value to Row v0

### Info

- Category: Table
- Requires Nested actions: False


### Description
Add a value at the next available space in a row, this will insert the value at the first available empty cell in the specified row or it will create a new column at the end of the row if necessary. This will modify the original table in place rather than return a new table.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Table | variable |  | True |  |
| Row to add value to | number |  | True |  |
| Value to add | text |  | True |  |
| New Column Name | text |  | False |  |
| Timeout (ms) | number |  | False | 30000 |
| Error on Timeout | checkbox |  | False | True |
| Fail On Error | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns
This action returns no results.

---