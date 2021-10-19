---
description: Move a file or folder somewhere else.
---

# Move File or Folder

{% swagger baseUrl="https://api.minehut.com" path="/file/{server-id}/move" method="post" summary="Move File or Folder" %}
{% swagger-description %}
Move a file or folder somewhere else.
{% endswagger-description %}

{% swagger-parameter in="header" name="authorization" type="string" %}
Your Minehut token.
{% endswagger-parameter %}

{% swagger-parameter in="header" name="x-session-id" type="string" %}
Your Minehut session id.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="files" type="array" %}
A list of file paths to move.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="movePath" type="string" %}
A file path to move the files to.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="overwrite" type="boolean" %}
Whether or not existing files should be overwritten by new files when being moved.
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
{"overwriteFiles":[...],"prevPath":"..."}
```
{% endswagger-response %}
{% endswagger %}
