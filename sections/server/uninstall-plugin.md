---
description: Remove a plugin from a server.
---

# Uninstall Plugin

{% api-method method="post" host="https://api.minehut.com" path="/server/{server-id}/remove\_plugin" %}
{% api-method-summary %}
Uninstall Plugin
{% endapi-method-summary %}

{% api-method-description %}
Remove a plugin from a server.
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
{% api-method-parameter name="plugin" type="string" required=true %}
The ID of the plugin you want to uninstall.
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

