---
description: Retrieve a list of all existing (manual) backups.
---

# List Backups

{% swagger baseUrl="https://api.minehut.com" path="/v1/server/{server-id}/backups" method="get" summary="List Backups" %}
{% swagger-description %}
Retrieve a list of all existing (manual) backups.
{% endswagger-description %}

{% swagger-parameter in="header" name="authorization" type="string" %}
Your Minehut token.
{% endswagger-parameter %}

{% swagger-parameter in="header" name="x-session-id" type="string" %}
Your Minehut session id.
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
{"backups":[{...}],"rolling_backup":{...}}
```
{% endswagger-response %}
{% endswagger %}
