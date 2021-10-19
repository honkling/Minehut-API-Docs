---
description: Searches for files and folders by name in a given directory.
---

# Search

{% swagger baseUrl="https://api.minehut.com" path="/file/{server-id}/search/{name}" method="get" summary="Search" %}
{% swagger-description %}
Searches for files and folders by name in a given directory.
{% endswagger-description %}

{% swagger-parameter in="header" name="authorization" type="string" %}
Your Minehut token.
{% endswagger-parameter %}

{% swagger-parameter in="header" name="x-session-id" type="string" %}
Your Minehut session id.
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
{"result":[{"id":"full path to file","name":"name of file with extension","directory":true/false},{...}]}
```
{% endswagger-response %}
{% endswagger %}
