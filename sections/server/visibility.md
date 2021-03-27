---
description: Modify a server's visibility to the server list.
---

# Visibility

{% api-method method="post" host="https://api.minehut.com" path="/server/{server-id}/visibility" %}
{% api-method-summary %}
Visibility
{% endapi-method-summary %}

{% api-method-description %}
Modify a server's visibility to the server list.
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
{% api-method-parameter name="visibility" type="boolean" required=true %}
Enables or disables the server's visibility.
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

