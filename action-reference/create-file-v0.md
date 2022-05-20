# Create File v0

### Info

- Category: File System
- Requires Nested actions: False


### Description
Create file with the given file name in the given directory.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Root Folder | file path |  | True |  |
| File Name | text |  | True |  |
| Overwrite? | checkbox |  | False | False |
| Fail on error? | checkbox |  | False | True |


### Interaction
Writes a new file on the Bot's filesystem.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| fullPath | String | ActionResult |

---