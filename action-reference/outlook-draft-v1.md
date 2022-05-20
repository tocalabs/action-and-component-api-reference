# Outlook Draft v1

### Info

- Category: Office 365
- Requires Nested actions: False


### Description
Draft an email in the specified Microsoft Outlook account.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Identity | variable |  | True |  |
| Recipient | text |  | True |  |
| Subject | text |  | False |  |
| Body | text |  | True |  |
| Has Attachments? | checkbox |  | False |  |
| Storage | select |  | True | local |
| File Path | file path |  | True |  |
| Attached File Name | text |  | False |  |
| Attachments | variable list |  | False |  |
| Timeout (milliseconds) | number |  | True | -1 |
| Error on Timeout? | checkbox |  | False |  |
| Fail on Error? | checkbox |  | False | True |
| Content Type | select |  | True | Text |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| emailId | String | ActionResult |

---