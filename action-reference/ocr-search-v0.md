# OCR Search v0

### Info

- Category: OCR
- Requires Nested actions: False


### Description
Extract any text in a region of the screen, search text can be provided to check if a region of the screen contains a certain word.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Selection | bounding box |  | True |  |
| Search Text (optional) | text |  | False |  |
| Language | select |  | True | eng |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error on timeout | checkbox |  | False | False |
| Error if no text found | checkbox |  | False |  |
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
| textValue | String | ActionResult |
| textFound | Boolean | ActionResult |
| image | Image | ActionResult |

---