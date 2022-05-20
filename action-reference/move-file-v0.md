# Move File v0

### Info

- Category: File System
- Requires Nested actions: False


### Description
Move file from one location on the Bot to another location on the same Bot.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| From File | file path |  | True |  |
| To Folder | file path |  | True |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action will move a file from one place to another on the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| destinationFile | String | ActionResult |

---