---
description: Upload a file to a server.
---

# Upload File

{% swagger baseUrl="https://{server-id}.manager.minehut.com" path="/file/upload//{file-name}" method="post" summary="Upload File" %}
{% swagger-description %}
Upload a file to a server.

Files are uploaded via Multipart Form Data.

Requires authorization.
{% endswagger-description %}

{% swagger-response status="200" description="" %}
```
{}
```
{% endswagger-response %}
{% endswagger %}
