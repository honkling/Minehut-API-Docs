---
description: Create a backup of a server.
---

# Create Backup

{% api-method method="post" host="https://api.minehut.com" path="/v1/server/{server-id}/backup/create" %}
{% api-method-summary %}
Create Backup
{% endapi-method-summary %}

{% api-method-description %}
Create a backup of a server.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-headers %}
{% api-method-parameter name="authorization" type="string" required=true %}
Your Minehut token.
{% endapi-method-parameter %}

{% api-method-parameter name="x-session-id" type="string" required=true %}
Your Minehut session id.
{% endapi-method-parameter %}
{% endapi-method-headers %}

{% api-method-body-parameters %}
{% api-method-parameter name="backup\_id" type="string" required=true %}
The ID of the new backup.
{% endapi-method-parameter %}
{% endapi-method-body-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
{"backups":[{...}],"rolling_backup":{...}}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

