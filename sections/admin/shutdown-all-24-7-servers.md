---
description: Forces all 24/7 servers to shutdown.
---

# Shutdown all 24/7 servers

{% swagger baseUrl="https://api.minehut.com" path="/admin/always_online/shutdown" method="post" summary="Shutdown all 24/7 servers" %}
{% swagger-description %}
Forces all 24/7 servers to shutdown.
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
