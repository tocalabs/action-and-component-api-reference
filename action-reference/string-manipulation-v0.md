# String Manipulation v0

### Info

- Category: Text
- Requires Nested actions: False


### Description
Run ${controls.manipulation.getItemName(parameters.manipulation)} on ${parameters.variable}


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Text to manipulate | text |  | False |  |
| Manipulation | select |  | True | trim |
| Pad Count | number |  | True | 1 |
| Pad Character | text |  | True |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| result | String | ActionResult |

---