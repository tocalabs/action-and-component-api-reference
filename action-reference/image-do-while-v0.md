# Image Do While v0

### Info

- Category: Vision
- Requires Nested actions: True


### Description
Execute sub-action(s) while image is either present or not, depending on the option selected for the "Loop while image is present?" input.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Selection | image |  | True |  |
| Region | bounding box |  | False |  |
| Loop while image is present? | checkbox |  | False |  |
| Colour sensitive? | checkbox |  | False |  |
| Timeout (milliseconds) | number |  | False | 30000 |
| Error on timeout? | checkbox |  | False | True |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| continueExecution | Boolean | ActionResult |
| rectangle | Array | ActionResult |
| image | Image | ActionResult |

---