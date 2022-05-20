# Delete Table Column v3

### Info

- Category: Table
- Requires Nested actions: False


### Description
Delete column from the table by specifying either the position of the column or name, returns a new table and the removed column as a list.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Table | variable |  | True |  |
| Column To Remove (Index or Name) | text |  | True |  |
| Fail On Error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| updatedTable | Table | ActionResult |
| removedColumn | Array | ActionResult |

---