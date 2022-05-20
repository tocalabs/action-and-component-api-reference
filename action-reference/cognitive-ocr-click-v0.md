# Cognitive OCR Click v0

### Info

- Category: AI
- Requires Nested actions: False


### Description
This will search for text using Microsoft's Cognitive OCR and click at the location where it finds the Search Text. 


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Search Text | text |  | True |  |
| Recognise handwriting? | checkbox |  | False |  |
| Region | bounding box |  | True |  |
| Offset | coordinates |  | False |  |
| Occurrence | number |  | True | 1 |
| Click Type | select |  | True | Left |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error on timeout? | checkbox |  | False |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action will simulate a mouse click.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| textToFind | String | ActionResult |
| regionValue | Image | ActionResult |

---