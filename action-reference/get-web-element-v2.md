# Get Web Element v2

### Info

- Category: Browser
- Requires Nested actions: False


### Description
Perform an interaction with a website open in a browser. Using this action you can get links and text and also perform mouse clicks and simulate text inputs.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Browser Alias | autocomplete |  | True |  |
| Element | web element |  | True |  |
| Interaction | select |  | True | data |
| Options | text |  | False |  |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error On Timeout | checkbox |  | False |  |
| Fail On Error | checkbox |  | False | True |


### Interaction
This action performs a mouse click/hover or types in text if the Click/Mouse Over or Send Keys interaction is selected.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| Image | Image | ActionResult |
| XPath | String | ActionResult |
| Rectangle | BoundingBox | ActionResult |
| Text | String | ActionResult |
| Link | String | ActionResult |
| TextList | Array | ActionResult |
| LinkList | Array | ActionResult |
| XPathList | Array | ActionResult |
| elementFound | Boolean | ActionResult |

---