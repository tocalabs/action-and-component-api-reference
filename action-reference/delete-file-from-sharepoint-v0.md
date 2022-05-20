# Delete File From SharePoint v0

### Info

- Category: Office 365
- Requires Nested actions: False


### Description
Delete a file from your sharepoint at the given path.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Identity | variable |  | True |  |
| Hostname | text |  | True |  |
| Site Path | text |  | True |  |
| Drive | text |  | False |  |
| Item Type | select |  | True | itemid |
| Path | text |  | True |  |
| Item ID | variable |  | True |  |
| Timeout (milliseconds) | number |  | True | -1 |
| Error on Timeout? | checkbox |  | False |  |
| Fail on Error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| itemId | String | ActionResult |
| itemName | String | ActionResult |

---