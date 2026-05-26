# SharePoint Lists

## Requests

Main list used to store employee service requests.

### Columns

| Column | Type |
|---|---|
| Title | Single line of text |
| RequestType | Choice |
| Description | Multiple lines of text |
| Priority | Choice |
| RequesterEmail | Single line of text |
| Department | Choice |
| Status | Choice |
| ManagerEmail | Single line of text |
| ApprovalComments | Multiple lines of text |
| CreatedDate | Date and Time |
| CompletedDate | Date and Time |

## RequestHistory

Audit log list used to track request lifecycle changes.

### Columns

| Column | Type |
|---|---|
| Title | Single line of text |
| RequestID | Number |
| Action | Single line of text |
| OldStatus | Single line of text |
| NewStatus | Single line of text |
| ChangedBy | Single line of text |
| ChangeDate | Date and Time |
| Comments | Multiple lines of text |