# Concatenate Tables v0

### Info

- Category: 
- Requires Nested actions: False


### Description
Join two tables together, similar to an SQL join, by either stacking the tables one on top of the other if their columns align, or stack them side by side if their columns do not match.



### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Table to join on | variable |  | True |  |
| Table to join | variable |  | True |  |
| Axis to concatenate on | select |  | False | 0 |
| Join type | select |  | False | inner |
| Fail On Error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| concatenatedTable | Table | ActionResult |

---