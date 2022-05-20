# Download From SharePoint v0

### Info

- Category: Office 365
- Requires Nested actions: False


### Description
Download file from a Sharepoint destination.


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
| Destination | file path |  | False |  |
| File name | text |  | False |  |
| Delete Remote File? | checkbox |  | False |  |
| Timeout (milliseconds) | number |  | True | -1 |
| Error on Timeout? | checkbox |  | False |  |
| Fail on Error? | checkbox |  | False | True |


### Interaction
This action downloads a file onto the Bot at the requested destination.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |

---