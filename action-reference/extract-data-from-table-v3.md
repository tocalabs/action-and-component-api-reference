# Extract Data from Table v3

### Info

- Category: Browser
- Requires Nested actions: False


### Description
Extract data from a table in a website, will only work on browsers which have been opened with the Open Browser action. 


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Browser Alias | autocomplete |  | True |  |
| Table name | text |  | True |  |
| Table | data table |  | True |  |
| Fail on error? | checkbox |  | False | True |
| Include iframes? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| ${parameters.tableName} | Table | ActivityVariable |

---