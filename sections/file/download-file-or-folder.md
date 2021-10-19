---
description: Download a file or directory located on your Minehut server.
---

# Download File or Folder

{% swagger baseUrl="https://api.minehut.com" path="/file/{server-id}/download" method="post" summary="Download File or Directory" %}
{% swagger-description %}
Download a file or directory located on your Minehut server.
{% endswagger-description %}

{% swagger-parameter in="header" name="authorization" type="string" %}
Your Minehut token.
{% endswagger-parameter %}

{% swagger-parameter in="header" name="x-session-id" type="string" %}
Your Minehut session id.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="files" type="array" %}
An array of file paths to download.
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
File (binary)
```
{% endswagger-response %}
{% endswagger %}
