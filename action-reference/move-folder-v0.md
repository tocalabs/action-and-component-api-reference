# Move Folder v0

### Info

- Category: File System
- Requires Nested actions: False


### Description
Move folder and it's contents from one location on the Bot to another.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| From Folder | file path |  | True |  |
| To Folder | file path |  | True |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action will move a folder from one location to another on the Bot's filesystem.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| destinationFolder | String | ActionResult |

---