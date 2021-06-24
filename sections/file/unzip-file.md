---
description: Extracts the contents of a .zip file. The extension must be .zip.
---

# Unzip File

{% hint style="info" %}
This endpoint is currently only available on Minehut's Developer Network, as it is currently being tested.
{% endhint %}

{% api-method method="post" host="https://api.dev.minehut.com" path="/file/{server-id}/unzip/{path}" %}
{% api-method-summary %}
Unzip File
{% endapi-method-summary %}

{% api-method-description %}
Extracts the contents of a .zip file. The extension must be .zip.
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
{}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

