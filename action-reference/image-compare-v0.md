# Image Compare v0

### Info

- Category: Vision
- Requires Nested actions: False


### Description
Compare two images and return true if the images are the same.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Source | image |  | True |  |
| Target | image |  | True |  |
| Match Confidence | range |  | True | 0.9 |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error on timeout? | checkbox |  | False | True |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| compareResult | Boolean | ActionResult |

---