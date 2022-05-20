# Regex Replace v0

### Info

- Category: Text
- Requires Nested actions: False


### Description
Replace text in ${parameters.inputString} that matches /${parameters.regexPattern}/${parameters.ignoreCase ? 'i' : ''}${parameters.multiline ? 'm' : ''} with ${parameters.replacement}


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Text | text |  | True |  |
| Regular Expression | text |  | True |  |
| Replacement | text |  | True |  |
| Ignore case? | checkbox |  | False |  |
| Multiline? | checkbox |  | False |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| result | String | ActionResult |

---