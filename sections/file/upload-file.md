---
description: Upload a file to a server.
---

# Upload File

{% swagger baseUrl="https://api.minehut.com" path="/file/upload/{server-id}//{file-name}" method="post" summary="Upload File" %}
{% swagger-description %}
Upload a file to a server.
{% endswagger-description %}

{% swagger-parameter in="header" name="authorization" type="string" %}
Your Minehut token.
{% endswagger-parameter %}

{% swagger-parameter in="header" name="x-session-id" type="string" %}
Your Minehut session id.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="file" type="object" %}
The file you want to upload. (binary)
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
{}
```
{% endswagger-response %}
{% endswagger %}
