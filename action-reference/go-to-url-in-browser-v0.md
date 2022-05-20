# Go to URL in Browser v0

### Info

- Category: Browser
- Requires Nested actions: False


### Description
Go to the specified URL in the browser, only works on browsers that have been opened with the Open Browser action.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| URL | text |  | True | https:// |
| Browser Alias | autocomplete |  | True |  |
| Timeout (milliseconds) | number |  | True | 30000 |
| Error on timeout? | checkbox |  | False |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action will load a page at the specified URL in a browser.

### Returns
This action returns no results.

---