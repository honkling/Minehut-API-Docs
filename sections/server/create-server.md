---
description: Create a Minehut server.
---

# Create Server

{% swagger baseUrl="https://api.minehut.com" path="/servers/create" method="post" summary="Create Server" %}
{% swagger-description %}
Create a new Minehut server.
{% endswagger-description %}

{% swagger-parameter in="header" name="authorization" type="string" %}
Your Minehut token.
{% endswagger-parameter %}

{% swagger-parameter in="header" name="x-session-id" type="string" %}
Your Minehut session id.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="name" type="string" %}
The name of the server.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="platform" type="string" %}
The server's platform (must be "java".)
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
{"server":{...}}
```
{% endswagger-response %}
{% endswagger %}
