---
description: Force a server to enter hibernation.
---

# Stop Server \(hibernation\)

{% api-method method="post" host="https://api.minehut.com" path="/server/{server-id}/destroy\_service" %}
{% api-method-summary %}
Stop Server \(hibernation\)
{% endapi-method-summary %}

{% api-method-description %}
Force a server to enter hibernation.
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

