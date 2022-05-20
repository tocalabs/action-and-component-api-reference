# Set Datastore Variable v1

### Info

- Category: Variable
- Requires Nested actions: False


### Description
Set variable ${parameters.variable} as ${parameters.variableType} to ${parameters.data} in datastore


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Datastore | select |  | True |  |
| Variable Name | text |  | True |  |
| Variable Type | select |  | True | String |
| Value | text |  | True |  |
| Value | number |  | True | 0 |
| Value | checkbox |  | False | False |
| Coordinates | coordinates |  | False |  |
| Bounding Box | bounding box |  | False |  |
| Image | image |  | False |  |
| Grid | grid |  | False |  |
| List | text |  | False |  |
| Delimiter | text |  | True | , |
| Table | variable |  | False |  |
| Headers (comma separated) | text |  | False |  |
| File | file path |  | False |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| variableName | String | ActionResult |
| dataStoreVariable | ${parameters.variableType} | ActionResult |

---