# Azure blob download v0

### Info

- Category: Azure
- Requires Nested actions: False


### Description
Download file from Azure blob storage


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Auth Method | select |  | True | connectionstring |
| Connection String | text |  | True |  |
| SAS Token | text |  | True |  |
| Account Name | text |  | True |  |
| Container name | text |  | True |  |
| Blob Path | text |  | False |  |
| Blob name | text |  | True |  |
| Rename Blob | text |  | False |  |
| Destination | file path |  | True |  |
| Delete from container once downloaded? | checkbox |  | False |  |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error on Timeout? | checkbox |  | False |  |
| Fail on Error? | checkbox |  | False | True |


### Interaction
This action will write a file to the desired filepath.

### Returns
This action returns no results.

---