---
description: Retrieve a list of all existing (manual) backups.
---

# List Backups

{% api-method method="get" host="https://api.minehut.com" path="/v1/server/{server-id}/backups" %}
{% api-method-summary %}
List Backups
{% endapi-method-summary %}

{% api-method-description %}
Retrieve a list of all existing \(manual\) backups.
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

