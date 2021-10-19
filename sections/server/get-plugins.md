---
description: Retrieve the list of all plugins.
---

# Get Plugins

{% swagger baseUrl="https://api.minehut.com" path="/server/{server-id}/plugins" method="get" summary="Get Plugins" %}
{% swagger-description %}
Retrieve the list of all plugins.
{% endswagger-description %}

{% swagger-parameter in="header" name="authorization" type="string" %}
Your Minehut token.
{% endswagger-parameter %}

{% swagger-parameter in="header" name="x-session-id" type="string" %}
Your Minehut session id.
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
{"plugins":[{...}]}
```
{% endswagger-response %}
{% endswagger %}
