# Read Text In File v0

### Info

- Category: File System
- Requires Nested actions: False


### Description
Read text from file at ${parameters.path}


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
| readText | String | ActionResult |
| listText | Array | ActionResult |
| lineCount | Number | ActionResult |

---