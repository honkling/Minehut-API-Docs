---
description: Creates a folder.
---

# Create Folder

{% swagger baseUrl="https://api.minehut.com" path="/file/{server-id}/folder/create" method="post" summary="Create Folder" %}
{% swagger-description %}
Creates a folder.
{% endswagger-description %}

{% swagger-parameter in="header" name="authorization" type="string" %}
Your Minehut token.
{% endswagger-parameter %}

{% swagger-parameter in="header" name="x-session-id" type="string" %}
Your Minehut session id.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="directory" type="string" %}
The path for the folder to be created in.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="name" type="string" %}
The name of the folder.
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
{}
```
{% endswagger-response %}
{% endswagger %}
