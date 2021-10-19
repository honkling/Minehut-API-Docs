---
description: Renames a file or folder.
---

# Rename File or Folder

{% swagger baseUrl="https://api.minehut.com" path="/file/{server-id}/rename/{path}" method="post" summary="Rename File or Folder" %}
{% swagger-description %}
Renames a file or folder.
{% endswagger-description %}

{% swagger-parameter in="header" name="authorization" type="string" %}
Your Minehut token.
{% endswagger-parameter %}

{% swagger-parameter in="header" name="x-session-id" type="string" %}
Your Minehut session id.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="name" type="string" %}
The new name of the file or folder.
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
{}
```
{% endswagger-response %}
{% endswagger %}
