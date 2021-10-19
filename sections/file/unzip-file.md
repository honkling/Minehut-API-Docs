---
description: Extracts the contents of a .zip file. The extension must be .zip.
---

# Unzip File

{% swagger baseUrl="https://api.minehut.com" path="/file/{server-id}/unzip/{path}" method="post" summary="Unzip File" %}
{% swagger-description %}
Extracts the contents of a .zip file. The extension must be .zip.
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
