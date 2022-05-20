# If Then v3

### Info

- Category: Flow Control
- Requires Nested actions: True


### Description
Execute sub-action(s) if the expression is evaluated as true, skip sub-action(s) if the expression is evaluated as false. Any datachips which represent text should be wrapped with double quotes.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Expression | text |  | True |  |
| Timeout (milliseconds) | number |  | True | -1 |
| Error on timeout? | checkbox |  | False |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| result | Boolean | ActionResult |

---