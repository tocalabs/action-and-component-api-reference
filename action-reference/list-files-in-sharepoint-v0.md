# List Files In SharePoint v0

### Info

- Category: Office 365
- Requires Nested actions: False


### Description
List files from a folder or drive in sharepoint.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Identity | variable |  | True |  |
| Hostname | text |  | True |  |
| Site Path | text |  | True |  |
| Drive | text |  | False |  |
| Path | text |  | False |  |
| Table Name | text |  | True |  |
| Max Items | number |  | True | 100 |
| Include Folders | checkbox |  | False | True |
| Timeout (milliseconds) | number |  | True | -1 |
| Error on Timeout? | checkbox |  | False |  |
| Fail on Error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| Table Name | table | ActivityVariable |

---