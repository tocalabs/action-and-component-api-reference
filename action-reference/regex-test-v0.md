# Regex Test v0

### Info

- Category: Text
- Requires Nested actions: False


### Description
Check if ${parameters.inputString} matches /${parameters.regexPattern}/${parameters.ignoreCase ? 'i' : ''}${parameters.multiline ? 'm' : ''}


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Text | text |  | True |  |
| Regular Expression | text |  | True |  |
| Ignore case? | checkbox |  | False |  |
| Multiline? | checkbox |  | False |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| result | Boolean | ActionResult |

---