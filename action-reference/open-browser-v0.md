# Open Browser v0

### Info

- Category: Browser
- Requires Nested actions: False


### Description
Open a browser with an alias, a URL can be specified to open the browser to. The following browsers are supported:
- Chrome
- Firefox
- Internet Explorer


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Browser Type | select |  | True | Chrome |
| URL | text |  | False | https:// |
| Browser Alias | text |  | True |  |
| Maximize browser? | checkbox |  | False | True |
| Continue without waiting for page load? | checkbox |  | False |  |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error on timeout? | checkbox |  | False | False |
| Fail on error? | checkbox |  | False | True |
| Browser Extension | file path |  | False |  |
| How to handle alerts | select |  | False | accept |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| browserAlias | String | ActionResult |

---