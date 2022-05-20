# Get Cell Colour v0

### Info

- Category: Microsoft Excel
- Requires Nested actions: False


### Description
Get colour of a specific cell in an Excel workbook that has been opened with the Open Excel action.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| App Alias | text |  | True |  |
| Workbook Alias | text |  | True |  |
| Column | text |  | False |  |
| Row | text |  | False |  |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error on timeout? | checkbox |  | False |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| colour | String | ActionResult |

---