# Worksheet Action v1

### Info

- Category: Microsoft Excel
- Requires Nested actions: False


### Description
Perform ${parameters.excelAction} on Excel workbook ${parameters.excelWorkbookAlias} ${parameters.sheetName ? ('with sheet ' + parameters.sheetName) : ''}


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| App Alias | text |  | True |  |
| Workbook Alias | text |  | True |  |
| Action | select |  | True | AddSheet |
| Sheet Name | text |  | False |  |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error on timeout? | checkbox |  | False |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| success | Boolean | ActionResult |

---