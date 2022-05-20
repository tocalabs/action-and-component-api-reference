# Zip Folder v0

### Info

- Category: File System
- Requires Nested actions: False


### Description
Zip ${parameters.sourceDirectory} into ${parameters.destinationFile}


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Source Folder | file path |  | True |  |
| Destination File | file path |  | True |  |
| Compression Level | select |  | True | Optimal |
| Include base folder? | checkbox |  | False |  |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error on timeout? | checkbox |  | False |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| destinationFile | String | ActionResult |
| sourceDirectory | String | ActionResult |

---