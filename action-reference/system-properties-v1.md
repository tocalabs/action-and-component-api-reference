# System Properties v1

### Info

- Category: Advanced
- Requires Nested actions: False


### Description
Get current system properties


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Fail on Error? | checkbox |  | False | True |


### Interaction
This action performs no interaction with the Bot.

### Returns

| Output | Type | Global Variable |
| :--- | :---: | :---: |
| machineName | String | ActionResult |
| userName | String | ActionResult |
| userDomainName | String | ActionResult |
| platform | String | ActionResult |
| operatingSystemVersionString | String | ActionResult |
| servicePack | String | ActionResult |
| hostName | String | ActionResult |
| diskInformation | Table | ActionResult |
| ipv4NetworkAddress | array | ActionResult |
| ipv6NetworkAddress | array | ActionResult |

---