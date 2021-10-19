---
description: Change the properties of a server.
---

# Edit Server Properties

{% swagger baseUrl="https://api.minehut.com" path="/server/{server-id}/edit_server_properties" method="post" summary="Edit Server Properties" %}
{% swagger-description %}
Change the properties of a server.
{% endswagger-description %}

{% swagger-parameter in="header" name="" type="string" %}
Your Minehut token.
{% endswagger-parameter %}

{% swagger-parameter in="header" name="" type="string" %}
Your Minehut session id.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="field" type="string" %}
The name of the property.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="value" type="string" %}
The new value for the property.
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
{}
```
{% endswagger-response %}
{% endswagger %}
