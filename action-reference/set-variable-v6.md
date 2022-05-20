# Set Variable v6

### Info

- Category: Variable
- Requires Nested actions: False


### Description
Set variable ${parameters.variable} as ${parameters.variableType} to ${parameters.data}


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Variable Name | text |  | True |  |
| Variable Type | select |  | True | String |
| Value | text |  | False |  |
| Value | number |  | True | 0 |
| Value | checkbox |  | False | False |
| Coordinates | coordinates |  | False |  |
| Bounding Box | bounding box |  | False |  |
| Image | image |  | False |  |
| Grid | grid |  | False |  |
| Table | table |  | False |  |
| Delimeter | text |  | True | , |
| List | text |  | False |  |
| Date Time | text |  | False |  |
| Valid Date Formats | array |  | True |  |
| Fail on error? | checkbox |  | False | True |
| Redact action data? | checkbox |  | False |  |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| ${parameters.variable} | ${parameters.variableType} | ActivityVariable |
| variableName | String | ActionResult |

---