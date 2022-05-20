# Insert Table Column v0

### Info

- Category: Table
- Requires Nested actions: False


### Description
Insert a list as a column to a table.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Table | variable |  | True |  |
| New Column Name | text |  | True |  |
| Where to place Column (Index or Name) | text |  | True |  |
| Column Values | array |  | False |  |
| Allow Duplicate Column? | checkbox |  | False |  |
| Fail On Error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| rangeTable | Table | ActionResult |

---