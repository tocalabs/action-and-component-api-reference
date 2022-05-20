# List Blobs in Container v0

### Info

- Category: Azure
- Requires Nested actions: False


### Description
List files in an Azure Blob storage container.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Authorisation Method | select |  | True | connectionstring |
| Connection String | text |  | True |  |
| SAS Token | text |  | True |  |
| Account Name | text |  | True |  |
| Container name | text |  | True |  |
| Blob Path | text |  | False |  |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error on timeout? | checkbox |  | False |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| result | Boolean | ActionResult |
| blobList | Array | ActionResult |

---