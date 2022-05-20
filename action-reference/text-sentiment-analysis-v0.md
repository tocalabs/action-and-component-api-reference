# Text Sentiment Analysis v0

### Info

- Category: AI
- Requires Nested actions: False


### Description
Analyse sentiment of ${parameters.textInput}


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Text | text |  | True |  |
| Language | select |  | False | eng |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error on timeout? | checkbox |  | False | False |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| sentimentScore | Number | ActionResult |

---