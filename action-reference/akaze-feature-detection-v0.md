# AKAZE Feature Detection v0

### Info

- Category: AI
- Requires Nested actions: False


### Description
Searches for features in the image inside the defined region, this is an advanced image search feature as it will not look for an exact match but rather look for similar features.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Image | image |  | True |  |
| Region | bounding box |  | False |  |
| Number of features | number |  | True | 1 |
| Timeout | number |  | True | 30000 |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| found | Boolean | ActionResult |
| image | Image | ActionResult |

---