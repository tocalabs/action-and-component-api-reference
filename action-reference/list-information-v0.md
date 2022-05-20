# List Information v0

### Info

- Category: List
- Requires Nested actions: False


### Description
Get the following information from a list:
- Types of the items inside the list (Text/Number etc.)
- Size of the list


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| List | variable |  | True |  |
| Information | select |  | True | count |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| arrayCount | Number | ActionResult |
| arrayType | String | ActionResult |

---