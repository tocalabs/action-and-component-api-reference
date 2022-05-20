# OCR Grid to Table v3

### Info

- Category: OCR
- Requires Nested actions: False


### Description
Draw a grid over a table that appears on the screen, using OCR this action will read the text from the screen and return a table.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Table name | text |  | True |  |
| Grid | grid |  | True |  |
| Header row | select |  | False | 0 |
| Anchor | image |  | False |  |
| Region | bounding box |  | False |  |
| Template | image |  | False |  |
| Color sensitive? | checkbox |  | False |  |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error on timeout? | checkbox |  | False |  |
| Fail on error? | checkbox |  | False | True |
| Thresholding | checkbox |  | False |  |
| Median Blur | checkbox |  | False |  |
| Scale | number |  | True | 2 |
| Numbers only | checkbox |  | False |  |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| ${parameters.tableName} | Table | ActivityVariable |
| textFound | Boolean | ActionResult |

---