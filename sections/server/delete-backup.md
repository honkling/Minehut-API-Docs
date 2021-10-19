---
description: Delete an existing backup.
---

# Delete Backup

{% swagger baseUrl="https://api.minehut.com" path="/v1/server/{server-id}/backup" method="delete" summary="Delete Backup" %}
{% swagger-description %}
Delete an existing backup.
{% endswagger-description %}

{% swagger-parameter in="header" name="authorization" type="string" %}
Your Minehut token.
{% endswagger-parameter %}

{% swagger-parameter in="header" name="x-session-id" type="string" %}
Your Minehut session id.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="backup_id" type="string" %}
The ID of the backup.
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
{}
```
{% endswagger-response %}
{% endswagger %}
