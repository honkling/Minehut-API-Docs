---
description: Get a server's information using it's name or ID
---

# Get Server

{% swagger baseUrl="https://api.minehut.com" path="/server/{server-id}" method="get" summary="Get Server" %}
{% swagger-description %}
Get a server's information using it's name or ID.
{% endswagger-description %}

{% swagger-parameter in="path" name="byId" type="boolean" %}
Whether or not you want to search for the server using the name.
{% endswagger-parameter %}

{% swagger-parameter in="path" name="byName" type="boolean" %}
Whether or not you want to search for the server using the name.
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
{"server":{...}}
```
{% endswagger-response %}
{% endswagger %}
