---
description: List all files and folders in a directory.
---

# List Folder

{% swagger baseUrl="https://api.minehut.com" path="/file/{server-id}/list/{path}" method="get" summary="List directory" %}
{% swagger-description %}
List all files and folders in a directory.
{% endswagger-description %}

{% swagger-parameter in="header" name="authorization" type="string" %}
Your Minehut token.
{% endswagger-parameter %}

{% swagger-parameter in="header" name="x-session-id" type="string" %}
Your Minehut session id.
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
{"files":[{...}]}
```
{% endswagger-response %}
{% endswagger %}
