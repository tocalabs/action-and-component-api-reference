# Dropbox Upload v0

### Info

- Category: Utilities
- Requires Nested actions: False


### Description
Upload a file from the Bot to Dropbox.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Dropbox Access Token | text |  | True |  |
| Local file path to upload | text |  | True |  |
| Dropbox file path | text |  | True |  |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error on Timeout? | checkbox |  | False |  |
| Fail on Error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| displayName | String | ActionResult |
| email | String | ActionResult |
| fileRevision | String | ActionResult |

---