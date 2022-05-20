# File Conversion v0

### Info

- Category: File System
- Requires Nested actions: False


### Description
Convert a file either from Excel to CSV or CSV to Excel, this will not remove the original file.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Folder | file path |  | True |  |
| File Name | text |  | True |  |
| Conversion Type | select |  | True | 0 |
| Headings | number |  | False |  |
| Columns | text |  | False |  |
| Destination Folder | file path |  | False |  |
| New Filename | text |  | False |  |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error on timeout? | checkbox |  | False | False |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action will create a new file on the Bot which will either be a CSV or an XLSX file.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| dimensions | String | ActionResult |
| cellCount | Number | ActionResult |
| fileSize | Number | ActionResult |

---