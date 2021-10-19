---
description: >-
  Forces a server to stop and go into hibernation. Requires admin authentication
  as this will shut down any server requested.
---

# Force hibernate (admin)

{% swagger baseUrl="https://api.minehut.com" path="/server/{server-name}/destroy_service_admin" method="post" summary="Force hibernate (admin)" %}
{% swagger-description %}
Forces a server to shut down and go into hibernation.
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
