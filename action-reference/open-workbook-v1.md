# Open Workbook v1

### Info

- Category: Microsoft Excel
- Requires Nested actions: False


### Description
Open an Excel workbook inside an Excel application that you have opened with an Open Excel action.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| App Alias | text |  | True |  |
| Workbook Alias | text |  | True |  |
| Workbook File | file path |  | True |  |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error on timeout? | checkbox |  | False | False |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action will open a workbook inside Excel.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| excelWorkbookAlias | String | ActionResult |
| excelAlias | String | ActionResult |

---