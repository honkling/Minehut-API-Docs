---
description: Edit a file. Creates a new file if it doesn't already exist.
---

# Edit File

{% swagger baseUrl="https://api.minehut.com" path="/file/{server-id}/edit/{path}" method="post" summary="Edit File" %}
{% swagger-description %}
Edit a file. If the file doesn't exist, it will be created for you automatically.
{% endswagger-description %}

{% swagger-parameter in="header" name="authorization" type="string" %}
Your Minehut token.
{% endswagger-parameter %}

{% swagger-parameter in="header" name="x-session-id" type="string" %}
Your Minehut session id.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="content" type="string" %}
The new content of the file.
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
{}
```
{% endswagger-response %}
{% endswagger %}
