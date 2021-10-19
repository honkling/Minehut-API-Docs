---
description: Execute a command on a server.
---

# Send Command

{% swagger baseUrl="https://api.minehut.com" path="/server/{server-id}/command" method="post" summary="Send Command" %}
{% swagger-description %}
Execute a command on a server.
{% endswagger-description %}

{% swagger-parameter in="header" name="authorization" type="string" %}
Your Minehut token.
{% endswagger-parameter %}

{% swagger-parameter in="header" name="x-session-id" type="string" %}
Your Minehut session id.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="command" type="string" %}
The command to send.
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
{}
```
{% endswagger-response %}
{% endswagger %}
