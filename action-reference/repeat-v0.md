# Repeat v0

### Info

- Category: Flow Control
- Requires Nested actions: True


### Description
Execute sub-action(s) ${parameters.counter} time(s)


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Counter | number |  | True | 0 |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error on timeout? | checkbox |  | False |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| currentIteration | Number | ActionResult |
| total | Number | ActionResult |

---