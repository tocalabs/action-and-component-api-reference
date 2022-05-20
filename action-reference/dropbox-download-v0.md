# Dropbox Download v0

### Info

- Category: Utilities
- Requires Nested actions: False


### Description
Download a file onto the Bot from a location in Dropbox.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Dropbox Access Token | text |  | True |  |
| Path to file | text |  | True |  |
| Local file path | text |  | True |  |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error on Timeout? | checkbox |  | False |  |
| Fail on Error | checkbox |  | False | True |


### Interaction
This action downloads a file onto the bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| displayName | String | ActionResult |
| email | String | ActionResult |

---