# Image to Text v0

### Info

- Category: OCR
- Requires Nested actions: False


### Description
Use Optical Character Recognition (OCR) to extract and return the text found in an image.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Image | image |  | True |  |
| Timeout (milliseconds) | number |  | True | 30000 |
| Language | select |  | True | eng |
| Error on timeout? | checkbox |  | False |  |
| Fail on error? | checkbox |  | False | True |
| Thresholding | checkbox |  | False |  |
| Median Blur | checkbox |  | False |  |
| Scale | number |  | True | 1 |
| Numbers only | checkbox |  | False |  |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| image | Image | ActionResult |
| text | String | ActionResult |
| textFound | Boolean | ActionResult |

---