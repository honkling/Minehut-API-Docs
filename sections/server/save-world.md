---
description: Save a server's world.
---

# Save World

{% swagger baseUrl="https://api.minehut.com" path="/server/{server-id}/save" method="post" summary="Save World" %}
{% swagger-description %}
Save a server's world.
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
