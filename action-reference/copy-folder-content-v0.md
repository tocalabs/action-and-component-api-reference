# Copy Folder Content v0

### Info

- Category: File System
- Requires Nested actions: False


### Description
Copy content of the From Folder to the To Folder, this will include all files.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| From Folder | file path |  | False |  |
| To Folder | file path |  | True |  |
| Overwrite? | checkbox |  | False |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
Copy files from one folder to another on the Bot's filesystem.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| targetDirectory | String | ActionResult |

---