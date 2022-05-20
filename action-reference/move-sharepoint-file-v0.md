# Move SharePoint File v0

### Info

- Category: Office 365
- Requires Nested actions: False


### Description
Move a file from one location in Sharepoint to another in Sharepoint.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Identity | variable |  | True |  |
| Hostname | text |  | True |  |
| Site Path | text |  | True |  |
| Drive | text |  | False |  |
| Item Type | select |  | True | itemid |
| Item Path | text |  | True |  |
| Item ID | variable |  | True |  |
| Folder Type | select |  | True | path |
| Folder Path | text |  | True |  |
| Folder ID | variable |  | True |  |
| Timeout (milliseconds) | number |  | True | -1 |
| Error on Timeout? | checkbox |  | False |  |
| Fail on Error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns
This action returns no results.

---