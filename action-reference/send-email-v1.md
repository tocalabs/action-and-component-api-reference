# Send Email v1

### Info

- Category: Utilities
- Requires Nested actions: False


### Description
Send email '${parameters.emailSubject}' to ${parameters.emailTo}


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Email | text |  | True |  |
| Subject | text |  | False |  |
| Message | text |  | True |  |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error on Timeout? | checkbox |  | False |  |
| Fail on Error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| payload | String | ActionResult |

---