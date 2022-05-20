# Add to List v0

### Info

- Category: List
- Requires Nested actions: False


### Description
Add an item to the list at the start, end or custom position in the list. When specifying a custom position, recall that lists start at 0 NOT 1. This will modify the original list instead of outputting a new list.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| List | variable |  | True |  |
| Item | text |  | True |  |
| Position | select |  | True | last |
| Insert Index | number |  | True | 0 |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns
This action returns no results.

---