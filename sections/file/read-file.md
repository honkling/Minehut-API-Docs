---
description: Retrieve the content of an existing file.
---

# Read File

{% swagger baseUrl="https://api.minehut.com" path="/file/{server-id}/read/{path}" method="get" summary="Read File" %}
{% swagger-description %}
Retrieve the content of an existing file.
{% endswagger-description %}

{% swagger-parameter in="header" name="authorization" type="string" %}
Your Minehut token.
{% endswagger-parameter %}

{% swagger-parameter in="header" name="x-session-id" type="string" %}
Your Minehut session id.
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
{"content":"..."}
```
{% endswagger-response %}
{% endswagger %}
