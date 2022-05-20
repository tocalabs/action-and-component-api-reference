# Sort Table v0

### Info

- Category: Microsoft Excel
- Requires Nested actions: False


### Description
Sort by ${controls.type.getItemName(parameters.type)} between ${parameters.start} and ${parameters.end}


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| App Alias | text |  | True |  |
| Workbook Alias | text |  | True |  |
| Type | select |  | True | Row |
| Start | text |  | False |  |
| End | text |  | False |  |
| Sorts | select |  | True | Ascending |
| Timeout | number |  | True | 30000 |
| Error on timeout? | checkbox |  | False |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| success | Boolean | ActionResult |

---