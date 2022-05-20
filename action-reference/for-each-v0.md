# For Each v0

### Info

- Category: Flow Control
- Requires Nested actions: True


### Description
Execute sub-action(s) for each item in the given list, returns each item in the list every time it completes a loop.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| List | variable |  | True |  |
| Timeout | number |  | True | 30000 |
| Error on timeout? | checkbox |  | False | False |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| currentItemValue | String | ActionResult |
| total | Number | ActionResult |
| count | Number | ActionResult |

---