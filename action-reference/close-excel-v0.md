# Close Excel v0

### Info

- Category: Microsoft Excel
- Requires Nested actions: False


### Description
Close Excel application that has been opened with the given alias.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| App Alias | text |  | True |  |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error on timeout? | checkbox |  | False |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action will close an open Excel application.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| success | Boolean | ActionResult |

---