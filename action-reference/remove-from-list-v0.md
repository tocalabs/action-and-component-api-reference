# Remove from List v0

### Info

- Category: List
- Requires Nested actions: False


### Description
Remove ${parameters.position ? parameters.position + ' item' : 'item ' + (parameters.index + 1)} from the list


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| List | variable |  | True |  |
| Remove From | select |  | True | first |
| Index | number |  | True | 0 |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |

---