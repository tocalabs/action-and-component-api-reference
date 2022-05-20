# API Caller v2

### Info

- Category: Advanced
- Requires Nested actions: False


### Description
Make an API call to a remote end-point


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Transport | select |  | True |  |
| URL | text |  | True |  |
| Method | select |  | True |  |
| Body Type | select |  | True |  |
| Body | text |  | True |  |
| File | file path |  | True |  |
| Content Type | select |  | False | application/json |
| Accept | select |  | False | application/json |
| Error if not Success Code | checkbox |  | False | True |
| Timeout (Milliseconds) | number |  | False | 30000 |
| Redact action data? | checkbox |  | False |  |
| Use Authentication? | checkbox |  | False |  |
| Authentication Type | select |  | True |  |
| Bearer Token | variable |  | True |  |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| result | String | ActionResult |
| statusCode | String | ActionResult |

---