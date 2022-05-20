# Bounding Box from Numbers v1

### Info

- Category: Coords
- Requires Nested actions: False


### Description
Create a bounding box from four number inputs. If an existing bounding box is given as an input then you can choose to overwrite values of the existing box or add to them by ticking the Offset option. 


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Existing Bounding Box | bounding box |  | False |  |
| X Coordinate | number |  | False | 0 |
| Y Coordinate | number |  | False | 0 |
| Width | number |  | False | 0 |
| Height | number |  | False | 0 |
| Offset | checkbox |  | False |  |
| Fail on error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| boxFromNumbers | boundingbox | ActionResult |

---