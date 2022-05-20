# Download File v0

### Info

- Category: File System
- Requires Nested actions: False


### Description
Download file to path that is in the Tocabot cloud to the Bot's filesystem.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| File | variable |  | True |  |
| Destination path | file path |  | True |  |
| Timeout | number |  | False | 30000 |
| Error on Timeout? | checkbox |  | False | True |
| Fail on Error? | checkbox |  | False | True |


### Interaction
This action downloads a file to the given destination path on the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| destinationFile | String | ActionResult |

---