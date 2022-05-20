# Loop Files in Folder v1

### Info

- Category: File System
- Requires Nested actions: True


### Description
Execute sub-action(s) for each file in the given folder, on each loop it returns the current file.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Folder | file path |  | True |  |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error on timeout? | checkbox |  | False | False |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| currentFile | String | ActionResult |

---