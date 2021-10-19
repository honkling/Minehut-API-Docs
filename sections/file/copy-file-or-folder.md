---
description: >-
  Copies a file or folder. When copying, a new file or folder will be created
  with the name and "-Copy" appended to the end.
---

# Copy File or Folder

{% swagger baseUrl="https://api.minehut.com" path="/file/{server-id}/copy" method="post" summary="Copy File or Folder" %}
{% swagger-description %}
Copies a file or folder. When copying, a new file or folder will be created with the name and "-Copy" appended to the end.
{% endswagger-description %}

{% swagger-parameter in="header" name="authorization" type="string" %}
Your Minehut token.
{% endswagger-parameter %}

{% swagger-parameter in="header" name="x-session-id" type="string" %}
Your Minehut session id.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="copyPath" type="string" %}
A directory path to copy the files to. You cannot specify the name of the new file or folder here.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="files" type="array" %}
Files and folders to copy.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="overwrite" type="boolean" %}
Whether or not to overwrite previously existing files.
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
{}
```
{% endswagger-response %}
{% endswagger %}
