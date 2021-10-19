---
description: Rename your Minehut server.
---

# Rename Server

{% swagger baseUrl="https://api.minehut.com" path="/server/{server-id}/change_name" method="post" summary="Rename Server" %}
{% swagger-description %}
Rename your Minehut server.
{% endswagger-description %}

{% swagger-parameter in="header" name="authorization" type="string" %}
Your Minehut token.
{% endswagger-parameter %}

{% swagger-parameter in="header" name="x-session-id" type="string" %}
Your Minehut session id.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="name" type="string" %}
The new name for the server.
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
{}
```
{% endswagger-response %}
{% endswagger %}
