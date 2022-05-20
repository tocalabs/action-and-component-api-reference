# Get Table Cell v0

### Info

- Category: Table
- Requires Nested actions: False


### Description
Get the value of the table cell at the specified position.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Table | variable |  | True |  |
| Header | text |  | False |  |
| Row Index | number |  | True | 0 |
| Column Index | number |  | True | 0 |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| cellValue | String | ActionResult |

---