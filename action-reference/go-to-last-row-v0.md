# Go To Last Row v0

### Info

- Category: Microsoft Excel
- Requires Nested actions: False


### Description
Go to last row of the workbook in an Excel application.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| App Alias | text |  | True |  |
| Workbook Alias | text |  | True |  |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error on timeout? | checkbox |  | False |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action will automatically scroll and select the last row with data in it in the given Excel app.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| success | Boolean | ActionResult |

---