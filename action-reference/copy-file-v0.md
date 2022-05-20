# Copy File v0

### Info

- Category: File System
- Requires Nested actions: False


### Description
Copy a file from one location to another on the Bots filesystem.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| File | file path |  | True |  |
| To Folder | file path |  | True |  |
| Overwrite? | checkbox |  | False |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This copies a file on the Bot and pastes it at the given filepath.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| targetFile | String | ActionResult |

---