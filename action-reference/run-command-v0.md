# Run Command v0

### Info

- Category: Advanced
- Requires Nested actions: False


### Description
Execute command ${parameters.command}


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Command | text |  | True |  |
| Wait for exit | checkbox |  | False | True |
| Ignore errors? | checkbox |  | False |  |
| Timeout (milliseconds) | number |  | False | 30000 |
| Error on timeout? | checkbox |  | False |  |
| Fail on Error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| consoleOutput | String | ActionResult |
| errorOutput | String | ActionResult |

---