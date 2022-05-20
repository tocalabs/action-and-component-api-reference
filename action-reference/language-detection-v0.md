# Language Detection v0

### Info

- Category: AI
- Requires Nested actions: False


### Description
Analyse sentiment of a section of text using Microsoft's Cognitive Sentiment Analysis service. Will return a numeric score indicating whether the text is positive or negative.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Text | text |  | True |  |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error on timeout? | checkbox |  | False | False |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| languageList | Array | ActionResult |

---