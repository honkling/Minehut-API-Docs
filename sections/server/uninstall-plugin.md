---
description: Remove a plugin from a server.
---

# Uninstall Plugin

{% swagger baseUrl="https://api.minehut.com" path="/server/{server-id}/remove_plugin" method="post" summary="Uninstall Plugin" %}
{% swagger-description %}
Remove a plugin from a server.
{% endswagger-description %}

{% swagger-parameter in="header" name="authorization" type="string" %}
Your Minehut token.
{% endswagger-parameter %}

{% swagger-parameter in="header" name="x-session-id" type="string" %}
Your Minehut session id.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="plugin" type="string" %}
The ID of the plugin you want to uninstall.
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
{}
```
{% endswagger-response %}
{% endswagger %}
