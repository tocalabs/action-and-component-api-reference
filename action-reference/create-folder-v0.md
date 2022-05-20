# Create Folder v0

### Info

- Category: File System
- Requires Nested actions: False


### Description
Create folder with the name specified in the Folder Name input in the parent directory defined by the Root folder input.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Root Folder | file path |  | True |  |
| Folder Name | text |  | True |  |
| Overwrite? | checkbox |  | False |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
Create an empty folder on the Bot's filesystem.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| fullPath | String | ActionResult |

---