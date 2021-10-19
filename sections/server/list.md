---
description: List currently online servers (truncated.)
---

# List Servers

{% swagger baseUrl="https://api.minehut.com" path="/servers" method="get" summary="Get All Servers" %}
{% swagger-description %}
List currently online servers (truncated.)
{% endswagger-description %}

{% swagger-response status="200" description="" %}
```
{"servers":[...],"total_players":(...),"total-servers":(...)}
```
{% endswagger-response %}
{% endswagger %}
