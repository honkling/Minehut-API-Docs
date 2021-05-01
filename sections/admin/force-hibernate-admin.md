---
description: >-
  Forces a server to stop and go into hibernation. Requires admin authentication
  as this will shut down any server requested.
---

# Force hibernate \(admin\)

{% api-method method="post" host="https://api.minehut.com" path="/server/{server-name}/destroy\_service\_admin" %}
{% api-method-summary %}
Force hibernate \(admin\)
{% endapi-method-summary %}

{% api-method-description %}
Forces a server to shut down and go into hibernation.
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

