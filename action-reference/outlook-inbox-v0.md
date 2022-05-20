# Outlook Inbox v0

### Info

- Category: Office 365
- Requires Nested actions: False


### Description
Return emails from Outlook inbox based on the mailbox query.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Identity | variable |  | True |  |
| Email Table Name | text |  | True |  |
| Mailbox Query | text |  | False |  |
| Max number of results | number |  | True | 10 |
| Timeout (milliseconds) | number |  | True | -1 |
| Error on timeout? | checkbox |  | False |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| ${parameters.tableName} | Table | ActivityVariable |

---