# Key Input v1

### Info

- Category: Keyboard
- Requires Nested actions: False


### Description
Simulate pushing down/releasing/pressing the specified keys. If the Type is Press then the keys will be pressed down in the order they were specified and released in the reverse order.
This action should be used in cases where special keys or key combinations need to be used.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Keys | key input |  | True |  |
| Type | select |  | True | press |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action simulates keyboard inputs.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |

---