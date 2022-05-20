# Advanced List Manipulation v0

### Info

- Category: List
- Requires Nested actions: False


### Description
Perform a series of different queries on a list, using this action you can perform a query for the following:
- Contains
- Starts With
- Ends With
- Exact
- Not Exact
- Not Contains

And perform the following manipulations to the list:
- Distinct 
- Sort


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| List to query | variable |  | True |  |
| Output List Name | text |  | True |  |
| Query Type | select |  | True |  |
| Direction | select |  | False | asc |
| Text | text |  | False |  |
| Case Sensitive? | checkbox |  | False | True |
| Remove Empty Records? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| Output List Name | Array | ActivityVariable |

---