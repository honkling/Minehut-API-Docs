---
description: Deletes an existing file.
---

# Delete File

{% swagger baseUrl="https://api.minehut.com" path="/file/{server-id}/delete/{path}" method="post" summary="Delete File" %}
{% swagger-description %}
Deletes an existing file.
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
