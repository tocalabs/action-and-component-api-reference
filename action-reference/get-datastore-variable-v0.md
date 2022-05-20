# Get Datastore Variable v0

### Info

- Category: Variable
- Requires Nested actions: False


### Description
Find and return the variable from a datastore with the given variable name.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Datastore | select |  | True |  |
| Parameter Key | text |  | True |  |
| Type | select |  | True | String |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| ${parameters.paramKey} | ${parameters.variableType} | ActionResult |

---