# Rename Folder v0

### Info

- Category: File System
- Requires Nested actions: False


### Description
Rename folder ${parameters.folderToRename} to ${parameters.newName}


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Source Folder | file path |  | True |  |
| New Name | text |  | True |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| folderToRename | String | ActionResult |
| newFolderName | String | ActionResult |

---