# Word to PDF v0

### Info

- Category: Microsoft Word
- Requires Nested actions: False


### Description
Convert the file at ${parameters.filepath} to a PDF


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| File to convert | file path |  | True |  |
| New File | file path |  | False |  |
| Delete original file? | checkbox |  | False |  |
| Timeout | number |  | False | 30000 |
| Error on timeout? | checkbox |  | False |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| convertedPdf | String | ActionResult |

---