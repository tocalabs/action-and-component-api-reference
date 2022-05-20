# Get Table Information V2 v0

### Info

- Category: Table
- Requires Nested actions: False


### Description
Get information about the table including:
- Number of rows
- Number of columns
- Whether or not the table is empty
- The combined number of rows and columns
- The list of column names from the table


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Table | variable |  | True |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| rows | Number | ActionResult |
| columns | Number | ActionResult |
| empty | Boolean | ActionResult |
| size | Number | ActionResult |
| headers | Array | ActionResult |

---