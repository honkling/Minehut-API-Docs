---
description: Restore a server from a backup.
---

# Restore Server

{% swagger baseUrl="https://api.minehut.com" path="/v1/server/{server-id}/backup/apply" method="post" summary="Restore Server" %}
{% swagger-description %}
Restore a server from a backup.
{% endswagger-description %}

{% swagger-parameter in="header" name="authorization" type="string" %}
Your Minehut token.
{% endswagger-parameter %}

{% swagger-parameter in="header" name="x-session-id" type="string" %}
Your Minehut session id.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="backup_id" type="string" %}
The ID of the backup you want to apply.
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
{}
```
{% endswagger-response %}
{% endswagger %}
