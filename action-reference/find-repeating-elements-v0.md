# Find Repeating Elements v0

### Info

- Category: Browser
- Requires Nested actions: False


### Description
Find list of repeating elements by comparing two different elements on a web page.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Browser Alias | autocomplete |  | True |  |
| First Element | web element |  | True |  |
| Second Element | web element |  | False |  |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error On Timeout | checkbox |  | False |  |
| Fail On Error | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| repeatingXpathList | Array | ActionResult |

---