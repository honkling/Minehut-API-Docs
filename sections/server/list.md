---
description: List currently online servers (truncated.)
---

# List Servers

{% api-method method="get" host="https://api.minehut.com" path="/servers" %}
{% api-method-summary %}
Get All Servers
{% endapi-method-summary %}

{% api-method-description %}
List currently online servers \(truncated.\)
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
{"servers":[...],"total_players":(...),"total-servers":(...)}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

