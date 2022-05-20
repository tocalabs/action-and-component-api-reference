# Find Rows in Table v8

### Info

- Category: Table
- Requires Nested actions: False


### Description
Find rows in a table by searching for certain values in the specified column.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Table | variable |  | False |  |
| Table Name | text |  | True |  |
| Column to search in (Index or Name) | text |  | True |  |
| Values To Find | array |  | False |  |
| Fail On Error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| ${parameters.tableName} | Table | ActivityVariable |
| rows | Array | ActivityVariable |
| rowsFound | Boolean | ActionResult |

---