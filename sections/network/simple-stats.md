---
description: Returns player count, server count, the server cap, and RAM.
---

# Simple Stats

### Response

`{"player_count":(...),"server_count":(...),"server_max":(...),"ram_count":(...),"ram_max":(...)}`

{% swagger baseUrl="https://api.minehut.com" path="/network/simple_stats" method="get" summary="Simple Stats" %}
{% swagger-description %}
Returns player count, server count, the current server cap, and RAM.
{% endswagger-description %}

{% swagger-response status="200" description="" %}
```
{"player_count":(...),"server_count":(...),"server_max":(...),"ram_count":(...),"ram_max":(...)}
```
{% endswagger-response %}
{% endswagger %}
