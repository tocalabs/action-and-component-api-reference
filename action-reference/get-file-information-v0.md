# Get File Information v0

### Info

- Category: File System
- Requires Nested actions: False


### Description
Return information about a file on the Bot, you can return:
- Size of the file
- Name of the file
- Extension of the file
- File at the path exists
- Is the file read only?
- Created date
- Last accessed date
- Last modified date


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| File Path | file path |  | True |  |
| Type of Property | select |  | False | directoryname |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| result | Number/Boolean/Text | ActionResult |

---