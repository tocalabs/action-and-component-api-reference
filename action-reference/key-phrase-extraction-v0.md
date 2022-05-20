# Key Phrase Extraction v0

### Info

- Category: AI
- Requires Nested actions: False


### Description
Extract Key Phrases from a section of text using Microsoft's Cognitive Key Phrase Extraction service.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Text | text |  | True |  |
| Language | select |  | False | en |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error on timeout? | checkbox |  | False |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| keyphrases | Array | ActionResult |

---