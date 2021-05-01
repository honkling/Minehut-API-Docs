---
description: Forces all 24/7 servers to shutdown.
---

# Shutdown all 24/7 servers

{% api-method method="post" host="https://api.minehut.com" path="/admin/always\_online/shutdown" %}
{% api-method-summary %}
Shutdown all 24/7 servers
{% endapi-method-summary %}

{% api-method-description %}
Forces all 24/7 servers to shutdown.
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

