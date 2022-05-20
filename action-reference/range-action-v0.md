# Range Action v0

### Info

- Category: Microsoft Excel
- Requires Nested actions: False


### Description
Range action


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| App alias | text |  | True |  |
| Workbook alias | text |  | True |  |
| Action | select |  | True | Delete cells |
| Post action | select |  | True | Shift deleted cells |
| Start | text |  | False |  |
| End | text |  | False |  |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error on Timeout | checkbox |  | False |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| outputTable | Table | ActionResult |
| successfulCall | Boolean | ActionResult |

---