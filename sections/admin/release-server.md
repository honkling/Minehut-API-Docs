---
description: Releases a server from suspension.
---

# Release Server

{% swagger baseUrl="https://api.minehut.com" path="/admin/{server-name}/release" method="post" summary="Release Server" %}
{% swagger-description %}
Releases a server from suspension.
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
