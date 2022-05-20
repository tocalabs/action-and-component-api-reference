# Text To Columns v1

### Info

- Category: Table
- Requires Nested actions: False


### Description
Split ${parameters.column} to multiple columns on ${parameters.splitText}


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Table | variable |  | True |  |
| Column To Split (Index or Name) | text |  | True |  |
| Text to split on | text |  | True |  |
| New Column Names | array |  | True |  |
| Fail On Error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| splitTable | Table | ActionResult |

---