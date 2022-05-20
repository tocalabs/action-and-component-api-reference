# OCR Analysis v0

### Info

- Category: AI
- Requires Nested actions: False


### Description
Recognise handwriting or text from the screen.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Recognise Handwriting? | checkbox |  | False | False |
| Region | bounding box |  | True |  |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error on timeout? | checkbox |  | False |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| trimResult | String | ActionResult |
| wordBoxes | Array | ActionResult |
| wordList | Array | ActionResult |
| textFound | Boolean | ActionResult |

---