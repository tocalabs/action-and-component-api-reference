# Get Info of CSV/XLSX v0

### Info

- Category: File System
- Requires Nested actions: False


### Description
Get information about an Excel or CSV file, returns how many columns and rows are in the file and then the combined dimensions.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| File Path | file path |  | True |  |
| Fail If File Does Not Exist | checkbox |  | False | True |
| FailOnError | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| columnCount | Number | ActionResult |
| rowCount | Number | ActionResult |
| size | Number | ActionResult |

---