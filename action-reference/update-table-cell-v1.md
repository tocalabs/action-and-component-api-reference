# Update Table Cell v1

### Info

- Category: Table
- Requires Nested actions: False


### Description
Set the table cell at (${parameters.header}, ${parameters.rowIndex}) to ${parameters.value}


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Table | variable |  | True |  |
| Header | text |  | False |  |
| Row Index | text |  | False |  |
| Value | text |  | False |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| rowIndex | Number | ActionResult |
| headerIndex | String | ActionResult |
| header | Number | ActionResult |

---