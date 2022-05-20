# Image Grid v5

### Info

- Category: Vision
- Requires Nested actions: True


### Description
Draw a grid over an area of the screen and then iterate over the grid cell by cell executing the sub-action(s) every loop.
The grid iterates from left to right, top to bottom. 
If you add a template then the template is searched for in each cell and the sub-action(s) are only run if the template is found in the current cell.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Grid | grid |  | True |  |
| Anchor | image |  | True |  |
| Region | bounding box |  | False |  |
| Template | image |  | False |  |
| Color sensitive? | checkbox |  | False | False |
| Timeout (milliseconds) | number |  | True | -1 |
| Error on timeout? | checkbox |  | False | True |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| templateResult | Boolean | ActionResult |
| cellImage | Image | ActionResult |
| currentIteration | Number | ActionResult |
| cellBox | BoundingBox | ActionResult |
| _imagePayload | BoundingBox | ActionResult |
| cellCenter | Coordinates | ActionResult |

---