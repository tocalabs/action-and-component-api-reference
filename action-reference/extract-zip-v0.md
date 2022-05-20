# Extract Zip v0

### Info

- Category: File System
- Requires Nested actions: False


### Description
Decompress a zip file an extract the contents.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Zip File | file path |  | True |  |
| Destination Folder | file path |  | True |  |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error on timeout? | checkbox |  | False |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action will decompress a zip file to a folder on the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| sourceFile | String | ActionResult |
| destinationDirectory | String | ActionResult |

---