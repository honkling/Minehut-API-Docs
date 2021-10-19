---
description: Start a server.
---

# Start Server

{% swagger baseUrl="https://api.minehut.com" path="/server/{server-id}/start" method="post" summary="Start Server" %}
{% swagger-description %}
Start a server.
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
