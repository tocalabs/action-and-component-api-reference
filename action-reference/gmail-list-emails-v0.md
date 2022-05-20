# Gmail List Emails v0

### Info

- Category: Utilities
- Requires Nested actions: False


### Description
Return table of emails from a GMail inbox based on the provided search query.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Google Credentials File | file path |  | True | credentials.json |
| Email Table Name | text |  | True |  |
| Mailbox Query | text |  | False |  |
| Timeout | number |  | False | 30000 |
| Error on Timeout | checkbox |  | False |  |
| Fail On Error | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| Email Table Name | Table | ActionResult |

---