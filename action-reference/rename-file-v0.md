# Rename File v0

### Info

- Category: File System
- Requires Nested actions: False


### Description
Rename file to ${parameters.fileToRename} to ${parameters.newName}


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Source File | file path |  | True |  |
| New Name | text |  | True |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| fileToRename | String | ActionResult |
| newFile | String | ActionResult |

---