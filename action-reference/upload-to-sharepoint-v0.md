# Upload To SharePoint v0

### Info

- Category: Office 365
- Requires Nested actions: False


### Description
Upload file to ${parameters.hostName}


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Identity | variable |  | True |  |
| Hostname | text |  | True |  |
| Site Path | text |  | True |  |
| Drive | text |  | False |  |
| Path | text |  | False |  |
| File To Upload | file path |  | True |  |
| File name | text |  | False |  |
| Delete Local File? | checkbox |  | False |  |
| Timeout (milliseconds) | number |  | True | -1 |
| Error on Timeout? | checkbox |  | False |  |
| Fail on Error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| itemId | String | ActionResult |

---