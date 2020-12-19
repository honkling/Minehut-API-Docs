---
description: Create a backup of a server.
---

# Create Backup

## Endpoint Info

### URL Path

POST `/v1/server/{server-id}/backup/create`

### Body

`{"backup_id":"id of the backup"}`

### Requires Authorization?

Yes.

### Response

`{"backups":[{...}],"rolling_backup":{...}}`

