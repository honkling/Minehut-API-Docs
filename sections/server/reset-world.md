---
description: Reset a server's world.
---

# Reset World

{% swagger baseUrl="https://api.minehut.com" path="/server/{server-id}/reset_world" method="post" summary="Reset World" %}
{% swagger-description %}
Reset a server's world 
{% endswagger-description %}

{% swagger-parameter in="header" name="authorization" type="string" %}
Your Minehut token.
{% endswagger-parameter %}

{% swagger-parameter in="header" name="x-session-id" type="string" %}
Your Minehut session id.
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
{}
```
{% endswagger-response %}
{% endswagger %}
