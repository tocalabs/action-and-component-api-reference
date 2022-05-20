# Read Cell Formula v1

### Info

- Category: Microsoft Excel
- Requires Nested actions: False


### Description
Read formula from ${parameters.column}${parameters.row} in workbook ${parameters.excelWorkbookAlias}


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
| formula | String | ActionResult |

---