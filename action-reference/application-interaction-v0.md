# Application Interaction v0

### Info

- Category: Utilities
- Requires Nested actions: False


### Description
Interact with a desktop application using native bindings, use it to extract text, perform clicks and type text. Similar to Get Web Element action but instead of interacting with a browser it interacts with a desktop application.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Process Name | autocomplete |  | False |  |
| App Element | app element |  | False |  |
| Interaction | select |  | False |  |
| Row | number |  | False | 0 |
| Column | number |  | False | 0 |
| Menu Path | text |  | False |  |
| Select Item | text |  | False |  |
| Set Text | text |  | False |  |
| Mouse Button | select |  | False |  |
| Double click? | checkbox |  | False |  |
| Set Value | range |  | False | 50 |
| Check Button | checkbox |  | False | False |
| Timeout | number |  | False | 30000 |
| Error on Timeout? | checkbox |  | False |  |
| Fail on Error? | checkbox |  | False | True |


### Interaction
This action can perform mouse clicks or simulate keyboard inputs depending on the users selection of inputs.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| interaction | Boolean/Number/String/Array | ActionResult |
| rectangle | BoundingBox | ActionResult |
| image | Image | ActionResult |
| text | Array | ActionResult |

---