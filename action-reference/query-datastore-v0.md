# Query Datastore v0

### Info

- Category: Variable
- Requires Nested actions: False


### Description
Find variable called ${paramters.itemKey} in Datastore


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Datastore | select |  | True |  |
| Item Key | text |  | True |  |
| Item Type | select |  | True | String |
| Timeout | number |  | False | 30000 |
| Error On Timeout | checkbox |  | False | True |
| Fail On Error | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| ${parameters.itemKey} | ${parameters.itemType} | ActionResult |

---