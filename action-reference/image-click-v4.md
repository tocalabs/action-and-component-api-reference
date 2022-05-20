# Image Click v4

### Info

- Category: Vision
- Requires Nested actions: False


### Description
Click where the image is found on the screen.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Selection | image |  | True |  |
| Region | bounding box |  | False |  |
| Coordinates | coordinates |  | False |  |
| Click Type | select |  | True | Left |
| Color sensitive? | checkbox |  | False | False |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error on timeout? | checkbox |  | False | True |
| Fail on error? | checkbox |  | False | True |
| Threshold | number |  | True | 0.9 |


### Interaction
This action simulates a mouse click.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| rectangles | List | ActionResult |
| imageSearchStatus | Boolean | ActionResult |
| regionValue | Image | ActionResult |
| firstRectangle | BoundingBox | ActionResult |

---