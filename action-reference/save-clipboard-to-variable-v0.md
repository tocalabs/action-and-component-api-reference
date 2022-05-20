# Save Clipboard to Variable v0

### Info

- Category: Clipboard
- Requires Nested actions: False


### Description
Save clipboard data as ${parameters.objectType} to ${parameters.variableName}


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Type | select |  | True | text |
| Variable Name | text |  | True |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| variableName | String | ActionResult |
| ${parameters.variableName} | ${parameters.objectType === 'image' ? 'Image' : 'String'} | ActionResult |

---