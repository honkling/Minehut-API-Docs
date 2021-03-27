---
description: Reset a server's world.
---

# Reset World

## Endpoint Info

### URL Path

POST `/server/{server-id}/reset_world`

### Requires Authorization?

Yes.

{% api-method method="post" host="https://api.minehut.com" path="/server/{server-id}/reset\_world" %}
{% api-method-summary %}
Reset World
{% endapi-method-summary %}

{% api-method-description %}
Reset a server's world 
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

