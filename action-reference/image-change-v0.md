# Image Change v0

### Info

- Category: Vision
- Requires Nested actions: False


### Description
Keep inspecting a region of the screen at a regular interval and complete when a change occurs.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Interval (milliseconds) | number |  | True | 0 |
| Region | bounding box |  | True |  |
| Continue If Changed | checkbox |  | False |  |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error on timeout? | checkbox |  | False | True |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| resultString | String | ActionResult |
| initialImage | Image | ActionResult |
| updatedImage | Image | ActionResult |

---