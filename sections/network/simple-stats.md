---
description: 'Returns player count, server count, the server cap, and RAM.'
---

# Simple Stats

### Response

`{"player_count":(...),"server_count":(...),"server_max":(...),"ram_count":(...),"ram_max":(...)}`

{% api-method method="get" host="https://api.minehut.com" path="/network/simple\_stats" %}
{% api-method-summary %}
Simple Stats
{% endapi-method-summary %}

{% api-method-description %}
Returns player count, server count, the current server cap, and RAM.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
{"player_count":(...),"server_count":(...),"server_max":(...),"ram_count":(...),"ram_max":(...)}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

