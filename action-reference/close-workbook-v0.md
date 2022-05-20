# Close Workbook v0

### Info

- Category: Microsoft Excel
- Requires Nested actions: False


### Description
Close an Excel workbook inside the Excel application.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| App Alias | text |  | True |  |
| Workbook Alias | text |  | True |  |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error on timeout? | checkbox |  | False |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action will close a workbook inside of an Excel Application.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| success | Boolean | ActionResult |

---