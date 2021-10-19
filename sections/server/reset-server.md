---
description: Resets a server to a fresh state.
---

# Reset Server

{% swagger baseUrl="https://api.minehut.com" path="/server/{server-id}/reset_all" method="post" summary="Reset Server" %}
{% swagger-description %}
Completely delete all server files and reset your server.
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
