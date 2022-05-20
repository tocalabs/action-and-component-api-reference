# OCR Text Click v1

### Info

- Category: OCR
- Requires Nested actions: False


### Description
Use OCR to find search for text in a region of the screen and click where the text appears if the text is found.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Search Text | text |  | True |  |
| Click Type | select |  | True | Left |
| Region | bounding box |  | True |  |
| Language | select |  | False | eng |
| Occurence | number |  | True | 1 |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error on timeout? | checkbox |  | False |  |
| Fail on error? | checkbox |  | False | True |
| Thresholding | checkbox |  | False |  |
| Median Blur | checkbox |  | False |  |
| Scale | number |  | True | 2 |
| Numbers only | checkbox |  | False |  |
| Coordinates | offset |  | False |  |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| textFound | Boolean | ActionResult |
| foundText | String | ActionResult |
| image | Image | ActionResult |
| textCoordinates | Coordinates | ActionResult |
| textBox | BoundingBox | ActionResult |

---