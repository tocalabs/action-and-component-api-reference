# Advanced String Manipulation v1

### Info

- Category: Text
- Requires Nested actions: False


### Description
Perform one of the following changes to text:
- Split
- Substring
- Join
- Insert
- Replace
- Remove



### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Text To Manipulate | text |  | True |  |
| Manipulation | select |  | True | split |
| New Array Name | text |  | True |  |
| Text to split on | text |  | True |  |
| Match Text | array |  | True |  |
| Replace with | text |  | True |  |
| Insert at index | number |  | True | 0 |
| Text to insert | text |  | True |  |
| Start index | number |  | True | 0 |
| Length | number |  | False | 1 |
| Text to add | text |  | True |  |
| Additional text to add | text |  | False |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| Output List if manipulation is split otherwise Result | Array if manipulation is split else Text | ActionResult |

---