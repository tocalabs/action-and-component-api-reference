# OCR Grid v8

### Info

- Category: OCR
- Requires Nested actions: True


### Description
Draw a grid over an area of the screen and then iterate over the grid cell by cell executing the sub-action(s) every loop.
The grid iterates from left to right, top to bottom. The action will return the text it extracts from each cell.
If you add a template then the template is searched for in each cell and the sub-action(s) are only run if the template is found in the current cell.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Grid | grid |  | True |  |
| Anchor | image |  | False |  |
| Region | bounding box |  | False |  |
| Template | image |  | False |  |
| Color sensitive? | checkbox |  | False |  |
| Timeout (milliseconds) | number |  | True | -1 |
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
| _topY | Number | ActionResult |
| _topX | Number | ActionResult |
| text | String | ActionResult |
| textFound | Boolean | ActionResult |
| rectangle | BoundingBox | ActionResult |
| cellBox | BoundingBox | ActionResult |
| centreCoords | Coordinates | ActionResult |
| currentIteration | Number | ActionResult |

---