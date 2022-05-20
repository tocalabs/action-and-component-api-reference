# Image Search v0

### Info

- Category: Vision
- Requires Nested actions: False


### Description
Search for image on screen, a region can be specified to limit the area the Bot will search for the image.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Selection | image |  | True |  |
| Region | bounding box |  | False |  |
| Colour Sensitive | checkbox |  | False |  |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error on timeout? | checkbox |  | False | True |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| coordinates | Array | ActionResult |
| image | Image | ActionResult |
| count | Number | ActionResult |
| firstRectangle | BoundingBox | ActionResult |
| firstCoordinates | Coordinates | ActionResult |
| imageSearchStatus | Boolean | ActionResult |
| rectangles | Array | ActionResult |

---