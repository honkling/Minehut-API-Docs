---
description: Modify a server's visibility to the server list.
---

# Visibility

{% swagger baseUrl="https://api.minehut.com" path="/server/{server-id}/visibility" method="post" summary="Visibility" %}
{% swagger-description %}
Modify a server's visibility to the server list.
{% endswagger-description %}

{% swagger-parameter in="header" name="authorization" type="string" %}
Your Minehut token.
{% endswagger-parameter %}

{% swagger-parameter in="header" name="x-session-id" type="string" %}
Your Minehut session id.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="visibility" type="boolean" %}
Enables or disables the server's visibility.
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
{}
```
{% endswagger-response %}
{% endswagger %}
