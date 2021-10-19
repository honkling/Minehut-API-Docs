---
description: Force a server to enter hibernation.
---

# Stop Server (hibernation)

{% swagger baseUrl="https://api.minehut.com" path="/server/{server-id}/destroy_service" method="post" summary="Stop Server (hibernation)" %}
{% swagger-description %}
Force a server to enter hibernation.
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
