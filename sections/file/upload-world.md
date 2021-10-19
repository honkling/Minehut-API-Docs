---
description: Upload a zipped world to a server.
---

# Upload World

{% swagger baseUrl="https://api.minehut.com" path="/file/world/upload/{server-id}" method="post" summary="Upload World" %}
{% swagger-description %}
Upload a world to a server.
{% endswagger-description %}

{% swagger-parameter in="header" name="authorization" type="string" %}
Your Minehut token.
{% endswagger-parameter %}

{% swagger-parameter in="header" name="x-session-id" type="string" %}
Your Minehut session id.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="file" type="object" %}
The zipped world you want to upload. (binary)
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
{}
```
{% endswagger-response %}
{% endswagger %}
