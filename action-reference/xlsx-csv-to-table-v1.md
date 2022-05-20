# XLSX/CSV to Table v1

### Info

- Category: Table
- Requires Nested actions: False


### Description
Convert the ${controls.fileType.getItemName(parameters.fileType)} file to a table


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Table Name | text |  | True |  |
| File Type | select |  | True | xlsx |
| File | file path |  | True |  |
| Sheet | text |  | False |  |
| Header Index | number |  | True | 0 |
| Error when empty? | checkbox |  | False | False |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error on timeout? | checkbox |  | False |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| ${parameters.tableName} | Table | ActionResult |

---