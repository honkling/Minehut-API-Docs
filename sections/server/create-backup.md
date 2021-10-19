---
description: Create a backup of a server.
---

# Create Backup

{% swagger baseUrl="https://api.minehut.com" path="/v1/server/{server-id}/backup/create" method="post" summary="Create Backup" %}
{% swagger-description %}
Create a backup of a server.
{% endswagger-description %}

{% swagger-parameter in="header" name="authorization" type="string" %}
Your Minehut token.
{% endswagger-parameter %}

{% swagger-parameter in="header" name="x-session-id" type="string" %}
Your Minehut session id.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="backup_id" type="string" %}
The ID of the new backup.
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
{"backups":[{...}],"rolling_backup":{...}}
```
{% endswagger-response %}
{% endswagger %}
