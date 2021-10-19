---
description: Closes any server and suspends it.
---

# Suspend Server

{% swagger baseUrl="https://api.minehut.com" path="/admin/{server-name}/suspend" method="post" summary="Suspend Server" %}
{% swagger-description %}
Closes any server and suspends it.
{% endswagger-description %}

{% swagger-parameter in="header" name="authorization" type="string" %}
Your Minehut token.
{% endswagger-parameter %}

{% swagger-parameter in="header" name="x-session-id" type="string" %}
Your Minehut session id.
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
{}
```
{% endswagger-response %}
{% endswagger %}
