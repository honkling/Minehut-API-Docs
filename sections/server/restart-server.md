---
description: Restart a Minehut server.
---

# Restart Server

{% swagger baseUrl="https://api.minehut.com" path="/server/{server-id}/restart" method="post" summary="Restart Server" %}
{% swagger-description %}
Restart a Minehut server.
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
