# Write Table to SQL Table v0

### Info

- Category: Table
- Requires Nested actions: False


### Description
Write a table called ${parameters.tableName} to a database


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Table | variable |  | True |  |
| SQL Table Name | text |  | True |  |
| SQL Connection String | text |  | True |  |
| If table already exists? | select |  | False | fail |
| Include index column? | checkbox |  | False |  |
| Schema | text |  | False |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| table | Table | ActionResult |

---