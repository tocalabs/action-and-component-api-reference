# For Each Row v0

### Info

- Category: Table
- Requires Nested actions: True


### Description
Execute nested-action(s) for each row in the input table, returns each row every iteration.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Table | variable |  | True |  |
| Timeout (milliseconds) | number |  | True | -1 |
| Error on timeout? | checkbox |  | False |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| currentRow | Table | ActionResult |
| rowIndex | Number | ActionResult |

---