---
description: Renames a file or folder.
---

# Rename File or Folder

{% hint style="info" %}
This endpoint is currently only available on Minehut's Developer Network, as it is currently being tested.
{% endhint %}

{% api-method method="post" host="https://api.dev.minehut.com" path="/file/{server-id}/rename/{path}" %}
{% api-method-summary %}
Rename File or Folder
{% endapi-method-summary %}

{% api-method-description %}
Renames a file or folder.
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
{% api-method-parameter name="name" type="string" required=true %}
The new name of the file or folder.
{% endapi-method-parameter %}
{% endapi-method-body-parameters %}
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

