# Execute Macro v0

### Info

- Category: Microsoft Excel
- Requires Nested actions: False


### Description
Execute a macro in an Excel application.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| App alias | text |  | True |  |
| Workbook alias | text |  | True |  |
| Macro file path | file path |  | True |  |
| Macro name | text |  | True |  |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error on timeout | checkbox |  | False |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action runs the requested macro on the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| success | Boolean | ActionResult |

---