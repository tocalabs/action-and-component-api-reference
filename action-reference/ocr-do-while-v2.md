# OCR Do While v2

### Info

- Category: OCR
- Requires Nested actions: True


### Description
This searches a region of the screen for a specified piece of text, it will execute the sub-action(s) until it can no longer find the specified text.
If the "Loop while text is present?" option is not selected then it will execute the sub-action(s) until it can find the specified text.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Search Text | text |  | True |  |
| Region | bounding box |  | False |  |
| Loop while text is present? | checkbox |  | False |  |
| Timeout (milliseconds) | number |  | True | -1 |
| Language | select |  | False | eng |
| Error on timeout? | checkbox |  | False |  |
| Error if no text found? | checkbox |  | False |  |
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
| textFound | Boolean | ActionResult |
| image | Image | ActionResult |

---