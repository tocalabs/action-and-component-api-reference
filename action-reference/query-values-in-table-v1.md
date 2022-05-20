# Query Values in Table v1

### Info

- Category: Table
- Requires Nested actions: False


### Description
Run ${parameters.query} on table


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Table to join on | variable |  | True |  |
| Query | text |  | True |  |
| Fail On Error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| queriedTable | Table | ActionResult |

---