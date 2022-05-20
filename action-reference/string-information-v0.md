# String Information v0

### Info

- Category: Text
- Requires Nested actions: False


### Description
Run ${controls.manipulation.getItemName(parameters.manipulation)} on ${parameters.variable}


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Text To Inspect | text |  | True |  |
| Command | select |  | True | len |
| Value | text |  | True |  |
| Match Case | checkbox |  | False | False |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| result | ${['len', 'index'].includes(parameters.manipulation) ? 'Number' : 'Boolean'} | ActionResult |

---