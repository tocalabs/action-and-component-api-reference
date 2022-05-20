# Outlook Send v1

### Info

- Category: Office 365
- Requires Nested actions: False


### Description
Send an email either by constructing it inside this action or by sending a draft that was previously created with the Outlook Draft action.


### Inputs

| Input | Type | Allowed Types | Required |  Default Value |
| :--- | :---: | :---: | :---: | :---: |
| Email Type | select |  | True | new |
| Identity | variable |  | True |  |
| Email ID | variable |  | True |  |
| Recipient | text |  | True |  |
| Subject | text |  | False |  |
| Body | text |  | True |  |
| Timeout (milliseconds) | number |  | True | -1 |
| Has Attachments? | checkbox |  | False |  |
| Storage | select |  | True | local |
| File Path | file path |  | True |  |
| Attached File Name | text |  | False |  |
| Attachments | variable list |  | False |  |
| Error on Timeout? | checkbox |  | False |  |
| Fail on Error? | checkbox |  | False | True |
| Content Type | select |  | True | Text |


### Interaction
This action performs no interaction with the Bot.

### Returns
This action returns no results.

---