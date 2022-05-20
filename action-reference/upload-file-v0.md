# Upload File v0

### Info

- Category: File System
- Requires Nested actions: False


### Description
Upload file at the path: ${parameters.filePath}


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| File to upload | file path |  | False |  |
| Timeout | number |  | False | 30000 |
| Error on Timeout? | checkbox |  | False | True |
| Fail on Error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| fileId | file | ActionResult |

---