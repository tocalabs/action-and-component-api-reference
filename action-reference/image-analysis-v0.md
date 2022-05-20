# Image Analysis v0

### Info

- Category: AI
- Requires Nested actions: False


### Description
Analyse image in a region using Microsoft's Cognitive Image Analysis service.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Region | bounding box |  | True |  |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error on timeout? | checkbox |  | False |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| imageAnalysis | String | ActionResult |
| caption | String | ActionResult |
| tagList | Array | ActionResult |
| confidenceList | Array | ActionResult |
| faceList | Array | ActionResult |

---