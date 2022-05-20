# JSON Parser v0

### Info

- Category: Advanced
- Requires Nested actions: False


### Description
Deserialize a serialized JSON string to one of the following types:
- Coordinates
- Bounding Box
- Grid
- Table


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| JSON | text |  | True |  |
| Convert To | select |  | True |  |
| Table Name | text |  | True |  |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| result | Coordinates/Bounding Box/Grid/Table | ActionResult |
| Table Name | table | ActivityVariable |

---