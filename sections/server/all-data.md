---
description: Get all information of a server.
---

# All Data

{% swagger baseUrl="https://api.minehut.com" path="/server/{server-id}/all_data" method="get" summary="All Data" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="header" name="authorization" type="string" %}
Your Minehut token.
{% endswagger-parameter %}

{% swagger-parameter in="header" name="x-session-id" type="string" %}
Your Minehut session id.
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
[{...}]
```
{% endswagger-response %}
{% endswagger %}
