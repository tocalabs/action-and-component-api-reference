# Regex Match v1

### Info

- Category: Text
- Requires Nested actions: False


### Description
Pick out matches from ${parameters.inputString} with /${parameters.regexPattern}/${parameters.ignoreCase ? 'i' : ''}${parameters.multiline ? 'm' : ''}


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Text | text |  | True |  |
| Output Variable Name | text |  | True |  |
| Regular Expression | text |  | True |  |
| Ignore case? | checkbox |  | False |  |
| Multiline? | checkbox |  | False |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| ${parameters.variableName} | Array | ActivityVariable |

---